<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-success">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Gestion Academica</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Estudiantes
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">

            <li><router-link to="/" class="dropdown-item">Listar estudiantes</router-link></li>
            <li><router-link to="/createE" class="dropdown-item">Registrar nuevo</router-link></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>
<div class="container-fluid">
  <router-view/>
</div>
</template>

<style>

</style>
