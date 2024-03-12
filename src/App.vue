<script>

</script>

<template>
  <div class="app">

    <!-- Barra de navegación -->
    <navVar />

    <!-- Inicio -->
    <inicio id="inicio" />

    <!-- Sobre mí -->
    <sobreMi id="sobreMi" />

    <!-- Titulaciones -->
    <titulaciones id="titulaciones" />

    <!-- Web development -->
    <webDev id="webDev" />

    <!-- Redes y bases de datos -->
    <redes id="redes" />

    <!-- Pentesting -->
    <pentesting id="pentesting" />

    <!-- Contacto -->
    <contacto id="contacto" />
    
  </div>
</template>

<script setup>
import navVar from "./components/nav-var.vue"
import inicio from "./components/inicio.vue"
import sobreMi from "./components/sobreMi.vue"
import titulaciones from "./components/titulaciones.vue"
import webDev from "./components/webDeb.vue"
import redes from "./components/redes.vue"
import pentesting from "./components/pentesting.vue"
import contacto from "./components/contacto.vue"
</script>

<style lang="scss">

* {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
}

body {
  background-color: rgb(0, 0, 24);
}

/* Scrollbar */
::-webkit-scrollbar {
  width: 15px;
}

::-webkit-scrollbar-track {
  background: #191724; /* color del track */
}

::-webkit-scrollbar-thumb {
  background-color: #515268; /* color del thumb */
  border-radius: 20px;
  border: 3px solid #272435; /* crea un padding alrededor del thumb */
}

</style>
