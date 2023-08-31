<script setup>

</script>

<template>
<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <div class="container-fluid">
    <ul class="navbar-nav">
    <li class="nav-item">
    <h1 class="title">Bueno cortes</h1>
    </li>
      <li class="nav-item">
      <button class="btn btn-outline-primary">Ir para> <a href="#">catálogo</a> </button>
      </li>
      <li class="nav-item">
      <button class="btn btn-outline-primary"><a href="#"></a>agendamento</button>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="#">Sobre nós</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">feedback</a>
      </li>
    </ul>
  </div>
</nav>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<div id="demo" class="carousel slide" data-bs-ride="carousel">

<!-- Indicators/dots -->
<div class="carousel-indicators">
  <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
  <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
  <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
</div>

<!-- The slideshow/carousel -->
<div class="carousel-inner">
  <div class="carousel-item active">
    <img src="src/img/images.jpeg" alt="Los Angeles" class="d-block w-200">
  </div>
  <div class="carousel-item">
    <img src="src/img/l1.jpeg" alt="Chicago" class="d-block w-200">
  </div>
  <div class="carousel-item">
    <img src="src/img/l3.jpeg" alt="New York" class="d-block w-200">
  </div>
</div>

<!-- Left and right controls/icons -->
<button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
  <span class="carousel-control-prev-icon"></span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
  <span class="carousel-control-next-icon"></span>
</button>
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
margin-right:50%;
}
.d-block{
  margin-left: 45%;
  margin-bottom: 25%;
}






</style>
