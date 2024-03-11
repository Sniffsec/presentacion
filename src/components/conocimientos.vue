<script>

</script>

<template>
    <div id="conocimientos">
        <h1 class="titulo2"><img class="stars2" src="../assets/media/estrella.svg" alt="">Conocimientos</h1>
        <div id="webDevelopment">
            <h1 class="subtitulo webContent">Web development</h1>
            <p class="texto webContent">Este año me he empezado a interesar por el desarrollo web,
                me parece un área muy interesante en la cual hay infinidad de herramientas con las
                que se puede hacer el diseño de una página web. A mí siempre me ha gustado el diseño,
                y al ver que con el desarrollo web podía crear páginas y utilizar mis conocimientos
                de diseño, me llamó mucho la atención.</p>
            <div id="lenguajes" class="webContent">
                <img id="fotoPerfil" src="../assets/media/foto.png" alt="">
            </div>
        </div>
    </div>
</template>

<style>
#conocimientos {
    width: 100%;
    height: 100vh;
    background-color: rgb(0, 0, 24);
}

#webDevelopment {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    width: 100%;
    height: 28rem;
    background-color: rgb(8, 0, 78);
}

.webContent {
    max-width: 40rem;
    text-align: justify;
    line-height: 1.3;
}

#lenguajes {
    
}
</style>