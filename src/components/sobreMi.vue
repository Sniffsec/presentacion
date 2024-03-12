<script>

</script>

<template>
    <section id="sobreMi">
      <h1 class="titulo2"><img class="stars2" src="../assets/media/estrella.svg" alt="">Sobre mí</h1>
      <div id="content">
        <div class="Container">
          <p class="texto">Soy un estudiante de informática al que le gusta aprender nuevas tecnologias de diseño y programación ya sea front-end o back-end.
            Estoy acostumbrado a adaptarme a diferentes metodologias de trabajo y tengo una gran capacidad de aprendizaje.</p>
          <p class="texto">Mis puntos fuertes son el desarrollo web y el uso de GNU/Linux</p>
          <p class="textBotton">Por otra parte, en mi tiempo libre me gusta hacer mis propios proyectos, escuchar música he ir al gimnasio.</p>
        </div>
        <div class="Container">
          <p class="texto">Nombre: Álex</p>
          <p class="texto">Apellidos: Frías Angulo</p>
          <p class="texto">Residencia: Bilbao</p>
          <p class="textBotton">Veículo: Moto (A1)</p>
        </div>
      </div>
    </section>
</template>

<style>
#content {
    display: flex;
  max-width: 60rem;
}

#sobreMi {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 100vh;
}
</style>