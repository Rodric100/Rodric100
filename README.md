<!DOCTYPE html>
<html>
<head>
	<title>Mensaje de Amor</title>
	<style>
		/* Estilos para la pestaña */
		.tab {
			width: 100%;
			height: 30px;
			background-color: #f0f0f0;
			border: 1px solid #ccc;
			cursor: pointer;
		}
		
		/* Estilos para las flores */
		.flowers {
			width: 100%;
			height: 300px;
			background-image: url('https://picsum.photos/200/300');
			background-size: cover;
			background-position: center;
		}
	</style>
</head>
<body>
	<!-- Mensaje de amor -->
	<h1>Te amo, mi amor</h1>
	
	<!-- Pestaña que cambia de lado -->
	<div class="tab" onclick="showFlowers()">Click aquí para ver las flores</div>
	
	<!-- Contenedor para las flores -->
	<div class="flowers" id="flowers"></div>
	
	<script>
		function showFlowers() {
			document.getElementById("flowers").style.display = "block";
		}
	</script>
</body>
</html>

<!---
Rodric100/Rodric100 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
