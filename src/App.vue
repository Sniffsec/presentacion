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
      <h1 class="titulo2"><stars />Sobre mí</h1>
      <contentContainer>
        <p class="bio">Soy un estudiante de informática al que le gusta aprender nuevas tecnologias de diseño y programación ya sea front-end o back-end.<br>
          Estoy acostumbrado a adaptarme a diferentes metodologias de trabajo y tengo una gran capacidad de aprendizaje.</p>
        <p style="color: white;">Mis puntos fuertes son el desarrollo web y el uso de GNU/Linux</p>
      </contentContainer>
    </div>

  </div>
</template>

<script setup>
import navVar from "./components/nav-var.vue"
import stars from "./components/stars.vue"
import contentContainer from "./components/container.vue"
</script>

<style lang="scss">



</style>
