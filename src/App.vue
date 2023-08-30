<script setup>

</script>

<template>
<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <div class="container-fluid">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
</nav>
 
 <div class="title">
 <h1>Bueno Cortes</h1>
 </div>


  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
  </div>
  
  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="l1.jpeg" alt="Los Angeles" class="d-block" style="width:30%">
    </div>
    <div class="carousel-item">
      <img src="images.jpeg" alt="Chicago" class="d-block" style="width:30%">
    </div>
    <div class="carousel-item">
      <img src="l3.jpeg" alt="New York" class="d-block" style="width:30%">
    </div>
  </div>
  
  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>

<div class="container-fluid mt-3">
  <h3>Carousel Example</h3>
  <p>The following example shows how to create a basic carousel with indicators and controls.</p>
</div>


<div class="mt-5 p-4 bg-dark text-white text-center">
  <p>Footer</p>
</div>
</template>

<style scoped>


.title{
margin-left: 38%;
margin-top: 2%;
font-family:'Times New Roman', Times, serif;
color: aqua;
}
.container-fluid{
margin-left: 37%;
}






</style>
