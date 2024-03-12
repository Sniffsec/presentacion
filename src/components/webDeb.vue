<script>

</script>

<template>
    <div id="webDev">
        <h1 class="titulo2"><img class="stars2" src="../assets/media/estrella.svg" alt="">Web development</h1>
        <div id="webDevelopment">
            
            <div class="container2">
            <p class="textBotton webContent">Este año me he empezado a interesar por el desarrollo web,
                me parece un área muy interesante en la cual hay infinidad de herramientas con las
                que se puede hacer el diseño de una página web. A mí siempre me ha gustado el diseño,
                y al ver que con el desarrollo web podía crear páginas y utilizar mis conocimientos
                de diseño, me llamó mucho la atención.</p>
            </div>
            <div class="webContent">
                <h2 id="lenguajesTitulo">Tecnologías</h2>
                <div id="father">
                    <label class="tecnologias" for=""><img class="logos" src="../assets/logos/vue.svg" alt="Vue.js">Vue.js</label>
                    <label class="tecnologias" for=""><img class="logos" src="../assets/logos/js.svg" alt="Js">Js</label>
                    <label class="tecnologias" for=""><img class="logos" src="../assets/logos/nodejs.svg" alt="Node.js">Node.js</label>
                    <label class="tecnologias" for=""><img class="logos" src="../assets/logos/aws.svg" alt="AWS">AWS</label>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
#webDev {
    width: 100%;
    height: 100vh;

}

#webDevelopment {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    align-items: center;
    flex-wrap: wrap;
    width: 100%;
    height: auto;
    font-size: large;
}

.webContent {
    display: flex;
    flex-direction: column;
    max-width: 45rem;
    text-align: justify;
    line-height: 1.3;
}

#lenguajesTitulo {
    color: white;
    text-align: center;
    margin-bottom: 1rem;
    margin-top: 2rem;
}

#father {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
}
</style>