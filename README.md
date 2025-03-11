<!DOCTYPE html>
<html>
<head>
	<title>JavaScript Example</title>
</head>
<body>
	<h1 id="header">Hello World!</h1>
	<button onclick="changeText()">Click Me</button>

	<script>
		function changeText() {
			document.getElementById("header").innerHTML = "JavaScript is awesome!";
		}
	</script>
</body>
</html>
