# carousel-animated
<!DOCTYPE html>
<html>
<head>
	<title>CAROUSEL</title>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    <style type="text/css">
    	.animate1{
    		animation-name: text1;
    		animation-duration: 4s;
    		/*animation-delay: 2s;*/
    		/*animation-timing-function: ease-out;*/
    	}
    	@keyframes text1{
    			from {
    				margin-left: 0px;
    				opacity:0;
  				}

  				to {
    				margin-left: 135px;
  				}
		}
		.animate2{
    		animation-name: text2;
    		animation-duration: 6s;
    		/*animation-delay: 2s;*/
    		/*animation-timing-function: ease-out;*/
    	}
    	@keyframes text2{
    			from {
    				margin-left: -20px;
    				/*visibility: hidden;*/
    				opacity: 0;
  				}

  				to {
    				margin-left: 0px;
  				}
		}
		.animate3{
    		animation-name: text3;
    		animation-duration: 4s;
    		/*animation-delay: 2s;*/
    		/*animation-timing-function: ease-out;*/
    	}
    	@keyframes text3{
    			from {
    				margin-left: 0px;
    				opacity:0;
  				}

  				to {
    				margin-left: 160px;
  				}
		}
		.animate4{
    		animation-name: text4;
    		animation-duration: 4s;
    		/*animation-delay: 2s*/
    		/*animation-timing-function: ease-out;*/
    	}
    	@keyframes text4{
    			from {
    				margin-bottom: 0px;
    				opacity:0;
  				}

  				to {
    				margin-bottom: 70px;
  				}
		}
		.carousel-caption{
			left: 12%;
    		text-align: left;  
    		max-width: 1000px;
    		right: auto;
    		padding:5px;
		}
</style>
</head>
<body>
	
	
<!-- slider -->
	<div id="my_carousel" class="carousel slide" data-ride="carousel" style="position: relative; margin-top: -20px; width:1200px; margin: 10px 90px;" >
		<!-- indicators -->
		<ol class="carousel-indicators">
			<li data-target="#my_carousel" data-slide-to="0" class="active"></li>
			<li data-target="#my_carousel" data-slide-to="1"></li>
			<!-- <li data-target="#my_carousel" data-slide-to="2"></li>
			<li data-target="#my_carousel" data-slide-to="3"></li> -->
		</ol>
		<!-- wrapper for slides -->
		<div class="carousel-inner">
			<div class="item active">
				<img src="shinchan.png" alt="FIRST AD">
				<div class="carousel-caption " >	
						<div style="font-size: 60px; font-weight: bolder; position: relative; margin:50px 0px 50px 135px; text-align: left; " class="animate1">HELLO</div>
						<div style="font-size: 80px; color: rgb(26,83,138);  margin:0px 0px 50px 0px;" class="animate2">I am Shinchan</div>
						<div style="margin:50px 0px 50px 160px;" class="animate3">To know more about me</div>
						<button type="button" style="padding:10px;color: rgb(11,162,232);  margin:50px 0px 70px 190px;" class="animate4" ><b><a href="https://en.wikipedia.org/wiki/Crayon_Shin-chan">Click here</a></b></button>
				</div>
			</div>
			<div class="item">
				<img src="doraemon.png" alt="SECOND AD">
				<div class="carousel-caption" style="text-align: left;">	
						<div style="font-size: 60px;  font-weight: bolder; position: relative; margin:50px 0px 50px 135px; " class="animate1">HELLO</div>
						<div style="font-size: 80px; color: rgb(26,83,138);  margin:0px 0px 50px 0px;" class="animate2">I am Doraemon</div>
						<div style="margin:50px 0px 50px 160px;" class="animate3">To know more about me</div>
						<button type="button" style="padding:10px;color: rgb(11,162,232); margin:50px 0px 70px 190px;" class="animate4" ><b><a href="https://en.wikipedia.org/wiki/Doraemon">Click here</a></b></button>
				</div>
			</div>
			<!-- <div class="item">
				
			</div>
			<div class="item">
				
			</div> -->
		</div>
		<a class="left carousel-control" href="#my_carousel" data-slide="prev">
			<span class="glyphicon glyphicon-chevron-left"></span>
    		<span class="sr-only">Previous</span>
		</a>
		<a class="right carousel-control" href="#my_carousel" data-slide="next">
			<span class="glyphicon glyphicon-chevron-right"></span>
			<span class="sr-only">Next</span>
		</a>
	</div>
</body>
</html>
