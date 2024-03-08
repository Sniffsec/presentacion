<template>
  <div class="app">

    <!-- Barra de navegación -->
    <navVar />

    <!-- Inicio -->
    <div id="inicio">
      
        <h1 class="titulo"><stars />Informático</h1>
        <img src="./assets/media/foto.png" alt="Foto de perfil" id="fotoPerfil">
        <button id="descargarCv">Descargar CV</button>
    </div>

    <!-- Sobre mí -->
    <div id="sobreMi">

    </div>

  </div>
</template>

<script setup>
import navVar from "./components/nav-var.vue"
import stars from "./components/stars.vue"
</script>

<style lang="scss">



</style>
