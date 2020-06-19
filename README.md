# Testing
I am testing this github
<!DOCTYPE html>
<html>
<head>
	<title>Media Queries</title>
	<style type="text/css">
		/** Basic Style **/
		h1{
			margin-bottom: 10px;
		}
		p{
			border: 1px solid black;
			margin-bottom: 15px;
		}
		#p1{
			background-color: skyblue;
			width: 300px;
			height: 300px;
		}
		#p2{
			background-color: green;
			width: 50px;
			height: 50px;
		}
		/** Large devices **/
		@media (min-width: 1200px)
		{
			#p1{
				width: 80%;
			}
			#p2{
				width: 150px;
				height: 150px;
			}
		}
		/** Medium Devices **/
		@media (min-width: 992px) and (max-width: 1199px)
		{
			#p1{
				width: 50%;
			}
			#p2{
				width: 100px;
				height: 100px;
			}
		}
	</style>
</head>
<body>
	<h1>Media Queries</h1>

	<p id="p1"></p>
	<p id="p2"></p>
</body>
</html>
