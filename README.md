# README
Hello Git
做了一些新的修改，在此基础上进行提交!
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	<style type="text/css">
		#hd{
			height: 260px;
			background: purple;
		}
	</style>
<script type="text/javascript">
window.onload = function(){
	

	var btn = document.getElementById("btn");
	var hd = document.getElementById("hd");
	

	btn.onclick = function(){


		var old_width = hd.style.width;

		var new_width = parseInt(old_width)+10;


		hd.style.width = new_width+'px';
		
	}
	
}

	
</script>
	</head>
	<body>
		
		<input type="button" id="btn" value="点我啊！" />
		<br /><br />
		
		<div id="hd" style="width: 300px;"></div>
	</body>
</html>



