

<html>

<head>
<!--background-->
<style>
body {
  background-image: url("mission-background-image.png");
}
</style>

<!--add a head-->
<style>
h1 {
  text-align: center;
}
<h1 style="color:Aqua;">What To Eat?</h1>
<hr>
</head>
<style>
<!--add a Background-->






<body>


<hr>
<div class="row">
    <div class="column"> 
 <!--add paragraph--> 
<p style="background-color:LightCyan;">When you don't know what to eat, 
take a look at these delicious foods, and then prepare these ingredients to make a rich dinner.</p>
<hr>
<h3 style="Color:LightPink;">1:XiaoLongBao</h3>
<img src="xiaolongbao.jpg" alt ="Food" width="300">

<hr>

<ul>
  <li>Pork bones</li>
  <li>Flour</li>
  <li>Meat-Pork</li>
  <li>Vegetables</li>
  <li>Salt</li>
  <li>Sugar</li>
  <li>Ginger</li>
  <li>Oil</li>
  <li>Scallions</li>
  <li>Wine</li>
</ul>  
<hr>
<ol>
  <li>Put the pork bone in the pot, add water, onion, ginger, salt and wine, and stew for an hour</li>
  <li>Then put it in the refrigerator and cool it for 1-2 hours</li>
  <li>Add water and oil to flour, knead into dough and cover with plastic wrap</li>
  <li>Chop pork and vegetables into a bowl, add seasoning and stir</li>
  <li>Then divide the dough into small parts and roll it into circles with a rolling pin</li>
  <li>Put the stuffing and a spoonful of frozen broth into the rolled noodles, and then pinch.</li>
  <li>Put in steamer for 10-15 minutes</li>
</ol>

</div>
  </div>


<!--Automatic Slideshow-->
 
<h2>Really delicious</h2>
<p>Which One You Like</p>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="xiaolongbao.jpg" style="width:50%">
  <div class="text">XiaoLongBao</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="jidn.jpg" style="width:50%">
  <div class="text">Steamed Egg</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="Pizza.jpg" style="width:50%">
  <div class="text">Pizza</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>





</body>
</html>
                
