

<html>

<head>
<!--background-->
<style>
body {
  background-image: url("mission-background-image.png");
}
</style>

<!--add a head-->


<h1 style="color:Aqua;">What To Eat?</h1>
<hr>
</head>




<body>


<hr>

 <!--add paragraph--> 
<p style="background-color:LightCyan;">When you don't know what to eat, 
take a look at these delicious foods, and then prepare these ingredients to make a rich dinner.</p>
<hr>
<h3 style="Color:LightPink;">1:XiaoLongBao</h3>
<img src="xiaolongbao.jpg" alt ="Food" width="300">


<!--Add list ul and ol-->
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

<hr>
<h3 style="Color:LightPink;">2:Steamed Egg</h3>
<img src="jidn.jpg" alt ="Food" width="300">


<ul>
  <li>Egg</li>
  <li>Water</li>
  <li>Salt</li>
  <li>Green Onion</li>
  <li>Balsam oil</li>
  <li>Soy Sauce</li>
</ul>  

<hr>
<ol>
  <li>Break up the eggs in a bowl</li>
  <li>Add water and salt in the bowl Water:egg= 1:1</li>
  <li>put in steamer for 10min</li>
  <li> add soy sauce and green onlion on the top </li>  
</ol>

<hr>

<h3 style="Color:LightPink;">3: Pizza</h3>
<img src="Pizza.jpg" alt ="Food" width="300">


<ul>
  <li>(1/4 ounce) active dry yeast</li>
  <li>1 teaspoon sugar</li>
  <li>1 cups warm water</li>
  <li>1/4 cup canola oil</li>
  <li>1 teaspoon salt</li>
  <li> 4 cups all-purpose flour</li>
  <li>1/2 pound ground beef</li>
  <li>1 small onion, chopped</li>
  <li>(15 ounces) tomato sauce</li>
  <li>3 teaspoons dried oregano</li>
  <li>1 teaspoon dried basil</li>
  <li>1 medium green pepper, diced</li>
  <li>2 cups shredded part-skim mozzarella cheese</li>
</ul>  

<hr>
<ol>
  <li>In large bowl, dissolve yeast and sugar in water; let stand for 5 minutes. Add oil and salt. Stir in flour, a cup at a time, until a soft dough forms.</li>
  <li>Turn onto floured surface; knead until smooth and elastic, about 2-3 minutes. Place in a greased bowl, turning once to grease the top. Cover and let rise in a warm place until doubled, about 45 minutes. Meanwhile, cook beef and onion over medium heat until no longer pink; drain.</li>
  <li>Punch down dough; divide in half. Press each into a greased 12-in. pizza pan. Combine the tomato sauce, oregano and basil; spread over each crust. Top with beef mixture, green pepper and cheese.</li>
  <li> Bake at 400° for 25-30 minutes or until crust is lightly browned. </li>  
</ol>



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
                
