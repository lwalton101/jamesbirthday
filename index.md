<html>
<head>
<title>Page Title</title>
<style>
.container { 
  height: 75px;
  width: 450px;
  position: relative;
  border: 3px solid green; 
}

.center {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.imgButton{
  text-align:center;
}
</style>
</head>
<body>
<div id="myDIV" class="container">
<h1>HAPPY HAPPY BIRTHDAY!</h1>
</div>

<div class="center">
<audio id="hb_audio" src="happybirthday.mp3" loop="loop"></audio>
<script src="confetti.js"></script>

<script>
function startBirthday() {
  startConfetti();
  document.getElementById("hb_audio").play();
}

function stopBirthday(){
	stopConfetti();
	document.getElementById("hb_audio").pause();
}
</script>
<div class="center">
<img src="unicorncake.jpg" alt="SO CUTTEEE" width="250" height"300">
</div>

<div class="center">
<button onclick="startBirthday();">Start</button>

<button onclick="stopBirthday();">Stop</button>
</div>

</div>
</body>
</html>
