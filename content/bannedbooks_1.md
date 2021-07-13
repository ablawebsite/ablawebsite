+++
title = "Banned Books in Prisons"
description = "Books Banned In Prisons and Jails"
date = "2021-06-30"
aliases = ["banned", "banned books"]
author = "AbLA"
+++
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  width: 50%;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">


<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="/images/thug.jpg" style="width:50%">
    <div class="text">Caption Text</div>

</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="/images/bluesteyes.jpg" style="width:50%">
  <div class="text">Caption Two</div>
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


###### Resources on banned books in prisons and jails

* [Disapproved Titles from Incarceration Facilities](https://docs.google.com/spreadsheets/d/1livnUApwrT97DGy5LcXishlXp68Rl3Jp/edit#gid=1464644036)
* [Sue Jeong Ka's The Banned Book List](http://suejeongka.com/index.php/the-banned-book-list/)
* [Prison Activist Resources: Books, Magazines & Publishers](https://www.prisonactivist.org/resources/books-magazines-and-publishers)
* [Books-to-prisoners: Outside Organizations](https://www.bookstoprisoners.net/outside-organizations/)
* [The Section of Disapproved Books with Daniel McCarthy Clifford](https://wam.umn.edu/incubator-project-with-daniel-mccarthy-clifford/)
* [Kate Cauley's Article "Banned Books behind Bars"](https://drive.google.com/file/d/1-bdu4lcmKF-iEzKg9YAozr1xMiAF02LG/view)

###### Webinars and Talks on Abolition