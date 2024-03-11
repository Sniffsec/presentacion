<template>
  <div class="app">

    <!-- Barra de navegación -->
    <navVar />

    <!-- Inicio -->
    <inicio />

    <!-- Sobre mí -->
    <sobreMi />

    <!-- Titulaciones -->
    <titulaciones />

    <!-- Conocimientos -->
    <conocimientos />

  </div>
</template>

<script setup>
import navVar from "./components/nav-var.vue"
import inicio from "./components/inicio.vue"
import sobreMi from "./components/sobreMi.vue"
import titulaciones from "./components/titulaciones.vue"
import conocimientos from "./components/conocimientos.vue"
</script>

<style lang="scss">

* {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
}

body {
  background-color: rgb(10, 0, 32);
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
