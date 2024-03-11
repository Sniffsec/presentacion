<script>
</script>

<template>
    <div id="inicio">
      <h1 id="titulo"><img class="stars" src="../assets/media/estrella.svg" alt="">Informático</h1>
      <img src="../assets/media/foto.png" alt="Foto de perfil" id="fotoPerfil">
      <button id="descargarCv">Descargar CV</button>
    </div>
</template>

<style>
#titulo {
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(45deg, rgb(0, 92, 230), 60%, rgb(0, 199, 116));
  background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;
  font-size: 3rem;
  margin-top: 4rem;
  margin-bottom: 2rem;
}

#inicio {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100vh;
}

#fotoPerfil {
  width: 15rem;
  height: auto;
  border-radius: 100%;

}

#descargarCv {
  color: white;
  font-weight: bold;
  padding: 0.3rem 0.5rem;
  margin-top: 2rem;
  border-radius: 0.5rem;
  background: linear-gradient(45deg, blue, 40%, purple);
  border-style: none;
}
</style>