<!DOCTYPE html>
<html>
<head>
	<script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Lab1 Krasilnik</title>
</head>
<body>
	<a-scene>
		<a-torus position="-2 1 -5" color="green" radius="1.2"></a-torus>
		<a-cylinder color="yellow" height="2" radius="0.05" position="-2 -1 -5"></a-cylinder><a-cylinder color="blue" height="2" radius="0.05" position="-3 -1 -5"></a-cylinder>
		<a-torus-knot color="orange" radius="1.2" position="-3 1 -5"></a-torus-knot>
		<a-plane width="9" height="2" position="3 1 -9"></a-plane>
		<a-text value="First WR!" color="black" width="10" position="-0.5 1 -6"></a-text>
		<a-plane width="7" height="7" rotation="-50 0 0" position="-2 -2 -5" color="purple"></a-plane>
		<a-sky color="grey"></a-sky>
	</a-scene>
</body>
</html>
