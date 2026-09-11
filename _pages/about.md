---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a recent graduate of Cornell University with a bachelors degree in Environment and Sustainability, dedicated to pursuing a research based academic career. I am motivated by the need to address pressing technological and environmental issues, such as climate change, in a way that is fair to rural communities. I am motivated by how policy can be formed to balance rural values, and technological and environmental priorities. My current work focuses on perceptions of large scale solar development processes and agrivoltaics policy. To learn more about my undergraduate thesis and current papers in progress see "Papers".

When I am not working away on my computer you can find me outside, probably cross country skiing, but also running, climbing, backpacking, hammocking, etc.! I also play the cello and love to bake. 

---

<div class="slideshow-container">
  <div class="slide fade">
   <img src="{{ site.baseurl }}/images/slide_1.jpg" style="width:100%">
  </div>
  <div class="slide fade">
    <img src="{{ site.baseurl }}/images/slide_2.jpg" style="width:100%">
  </div>
  <div class="slide fade">
    <img src="{{ site.baseurl }}/images/slide_3.jpg" style="width:100%">
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<style>
.slideshow-container {
  max-width: 700px;
  position: relative;
  margin: auto;
}

.slide {
  display: none;
}

.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  background-color: rgba(0,0,0,0.4);
}

.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
</style>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("slide");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slides[slideIndex-1].style.display = "block";
}
</script>
