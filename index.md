<html>
<head>
<title>Page Title</title>
</head>
<body>
<div id="myDIV">
<h1>HAPPY HAPPY BIRTHDAY!</h1>

<audio id="hb_audio" src="happybirthday.mp3" loop="loop"></audio>


<script src="confetti.js"></script>


<script>
function startBirthday() {
  startConfetti();
  document.getElementById("hb_audio").play();
}

function stopBirthday(){
	stopConfetti();
	document.getElementById("hb_audio").pause;
}
</script>

<button onclick="startBirthday();">Start</button>

<button onclick="stopBirthday();">Stop</button>


</div>
</body>
</html>
