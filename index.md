# Dineth Hesara
## Software Engineering Intern
### Evolve Technologies Pvt Ltd
#### https://www.linkedin.com/in/dineth-pussewala
##### Follow me for more!
###### See ya 👋

![Welcome to Technology](https://thumbs.dreamstime.com/b/neon-sign-welcome-highly-technological-design-98374211.jpg)

<style>
		#box {
			width: 50px;
			height: 50px;
			background-color: blue;
			position: relative;
		}
	</style>
<div id="box"></div>

<script>
		var box = document.getElementById("box");
		var position = 0;
		var interval = setInterval(moveBox, 10);

		function moveBox() {
			position++;
			box.style.left = position + "px";
			if (position == 200) {
				clearInterval(interval);
			}
		}
	</script>
