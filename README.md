<!DOCTYPE html>
<html>
<head>
	<title>Photo Catalogue</title>
	<style>
		.grid-container {
			display: grid;
			grid-template-columns: repeat(3, 1fr);
			grid-gap: 10px;
		}
		
		.grid-item {
			background-color: #fff;
			border: 1px solid #ddd;
			padding: 10px;
			text-align: center;
		}
		
		.grid-item img {
			width: 100%;
			height: 150px;
			object-fit: cover;
			border-radius: 10px;
		}
		
		.grid-item:hover {
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
		}
	</style>
</head>
<body>
	<div class="grid-container">
		<div class="grid-item">
			<img src="D:\logo\0FuezEtVR1SEHiSWf7i3ZQ.jpeg" alt="Image 1">
			<p>Image 1 Description</p>
		</div>
		<div class="grid-item">
			<img src="image2.jpg" alt="Image 2">
			<p>Image 2 Description</p>
		</div>
		<div class="grid-item">
			<img src="image3.jpg" alt="Image 3">
			<p>Image 3 Description</p>
		</div>
		<div class="grid-item">
			<img src="image4.jpg" alt="Image 4">
			<p>Image 4 Description</p>
		</div>
		<div class="grid-item">
			<img src="image5.jpg" alt="Image 5">
			<p>Image 5 Description</p>
		</div>
		<div class="grid-item">
			<img src="image6.jpg" alt="Image 6">
			<p>Image 6 Description</p>
		</div>
		<!-- Add more grid items here -->
	</div>
</body>
</html>