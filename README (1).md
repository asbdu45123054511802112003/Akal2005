
<!DOCTYPE html>
<html>
<head>
	<title>Example</title>
</head>
<body>

<h1 id="header">Hello World!</h1>

<button onclick="changeText()">Click Me</button>

<script>
	function changeText() {
		document.getElementById("header").innerHTML = "New Text!";
	}
</script>

</body>
</html>
