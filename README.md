
<meta charset = "utf-8">
<body>
	<div id = "myRect" style = transition: all 1s"'>
		<img style = "width: 300px;" src = "him.png">
	</div>

		<img style="width: 280px; margin-top: -550px; float: right;  " src="her.png">

		<input type = "range" id = "myPicker" min = "10" max="1440">
		<h2> Take him to her </h2>
		<div id="rangeValue" style="margin-left: 50%"></div>

	<script>
		myPicker.onchange = function()
		{ myRect.style.marginLeft = myPicker.value + "px";
		rangeValue.innerHTML = myPicker.value; }
	</script>
	<style>
		body {background: skyblue;}
		input{margin-top: 200px; margin-left: 40%; width: 400px;}
		h2 {size: 1em; color: white; margin-left: 46%;}
	</style>
</body>
