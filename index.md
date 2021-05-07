<html>
<head>
<title>Page Title</title>
</head>
<body>
<div id="myDIV">
<h1>HAPPY HAPPY BIRTHDAY!</h1>

<audio id="hb_audio" src="happybirthday.mp3" loop="loop" muted="muted"></audio>


<script src="confetti.js"></script>


<script>
function startBirthday() {
  startConfetti();
  document.getElementById("hb_audio").play;
}
</script>

<button onclick="startBirthday();">Start</button>

<button onclick="stopConfetti();">Stop</button>


</div>
</body>
</html>
