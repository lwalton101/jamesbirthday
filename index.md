<html>
<head>
<title>Page Title</title>
</head>
<body onload="startConfetti();">

<h1>HAPPY HAPPY BIRTHDAY!</h1>

<script src="confetti.js"></script>

<audio id="hb_audio" src="happybirthday.mp3" loop="loop"></audio>

<script>
window.onload = function() {
    document.getElementById("hb_audio").play();
}
</script>

<button onclick="startConfetti();">Start</button>

<button onclick="stopConfetti();">Stop</button>



</body>
</html>
