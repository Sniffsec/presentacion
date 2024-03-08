<template>
  <div class="app">

    <!-- Barra de navegación -->
    <navVar />

    <!-- Inicio -->
    <div id="inicio">
      <h1 class="titulo flex"><stars />Informático</h1>
      <img src="./assets/media/foto.png" alt="Foto de perfil" id="fotoPerfil">
      <button id="descargarCv">Descargar CV</button>
    </div>

    <!-- Sobre mí -->
    <div id="sobreMi">
      <h1 class="titulo2 flex"><stars />Sobre mí</h1>
      <div class="flex max">
        <contentContainer>
          <p class="texto">Soy un estudiante de informática al que le gusta aprender nuevas tecnologias de diseño y programación ya sea front-end o back-end.
            Estoy acostumbrado a adaptarme a diferentes metodologias de trabajo y tengo una gran capacidad de aprendizaje.</p>
          <p class="texto">Mis puntos fuertes son el desarrollo web y el uso de GNU/Linux</p>
          <p style="color: white;">Por otra parte, en mi tiempo libre me gusta hacer mis propios proyectos, escuchar música he ir al gimnasio.</p>
        </contentContainer>
        <contentContainer style="min-width: 12rem;">
          <p class="texto">Nombre: Álex</p>
          <p class="texto">Apellidos: Frías Angulo</p>
          <p class="texto">Residencia: Bilbao</p>
          <p style="color: white;">Veículo: Moto (A1)</p>
        </contentContainer>
      </div>
    </div>

    <!-- Titulaciones -->
    <div id="titulaciones">
      <h1 class="titulo2 flex"><stars />Titulaciones</h1>
      <contentContainer style="flex-direction: row;">
        <div class="estudios texto">
          <p class="texto">Educacion Secundaria</p>
          <p class="texto">Técnico en Preimpresión Digital</p>
          <p style="color: white;">Técnico en ASIR</p>
        </div>
        <div class="estudios texto">
          <p class="texto">(Centro Uribe-Kosta BHI)</p>
          <p class="texto">(Centro Emilio Campuzano)</p>
          <p style="color: white;">(Centro Almi)</p>
        </div>
        <div class="estudios texto">
          <p class="texto">2018-2021</p>
          <p class="texto">2021-2023</p>
          <p style="color: white;">2023-cursando</p>
        </div>
      </contentContainer>
      <h1 class="subtitulo flex">Idiomas</h1>
      <contentContainer style="flex-direction: row;">
        <div class="estudios texto">
          <p class="texto">Ingles</p>
          <p style="color: white;">euskara</p>
        </div>
        <div class="estudios texto">
          <p class="texto">B1</p>
          <p style="color: white;">B2</p>
        </div>
        <div class="estudios texto">
          <p class="texto">(Sin título pero en proceso de obtencion del B2)</p>
          <p style="color: white;">()Titulación de HABE</p>
        </div>
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
