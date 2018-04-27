---
published: true
title: Botanical Garden
layout: post
---
Paleaku Gardens Peace Sanctuary
Honaunau-Napoopoo, Hawaii

<div class="row">
  <div class="column">
    <img src="https://raw.githubusercontent.com/sarahmckee24/sarahmckee24.github.io/master/images/FullSizeRender.jpg" alt="labyrinth" style="width:25%" onclick="openImg(this);">
  </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/sarahmckee24/sarahmckee24.github.io/master/images/IMG_0445.JPG" alt="Flower" style="width:25%" onclick="openImg(this);">
  </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/sarahmckee24/sarahmckee24.github.io/master/images/IMG_0453.JPG" alt="Tree" style="width:25%" onclick="openImg(this);">
  </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/sarahmckee24/sarahmckee24.github.io/master/images/IMG_4774.JPG" alt="Heart" style="width:25%" onclick="openImg(this);">
  </div>
</div>

<!-- The expanding image container -->
<div class="container">
  <!-- Close the image -->
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>

  <!-- Expanded image -->
  <img id="expandedImg" style="width:100%">

  <!-- Image text -->
  <div id="imgtext"></div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
    var expandImg = document.getElementById("expandedImg");
    var imgText = document.getElementById("imgtext");
    expandImg.src = imgs.src;
    imgText.innerHTML = imgs.alt;
    expandImg.parentElement.style.display = "block";
}
</script>
