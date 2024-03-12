<template>
    <div id="nav-var">
        <div id="container">
            <h4 @click="inicio">inicio<div class="subMark"></div></h4>
            <h4 @click="sobreMi">Sobre mí<div class="subMark"></div></h4>
            <h4 @click="titulaciones">Titulaciones<div class="subMark"></div></h4>
            <h4 @click="webDev">Web dev<div class="subMark"></div></h4>
            <h4 @click="redes">Redes y DB<div class="subMark"></div></h4>
            <h4 @click="pentesting">Pentesting<div class="subMark"></div></h4>
            <h4 @click="contacto">Contacto<div class="subMark"></div></h4>
        </div>
        <div id="background">

        </div>
    </div>
</template>

<style lang="scss">
#nav-var {
    position: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;

    width: 100%;
    height: 5rem;

    z-index: 1;
}

#background {
    position: absolute;
    background-color: rgba(185, 185, 255, 0.08);
    width: 50rem;
    height: 3rem;
    border-radius: 1rem;
    margin-top: 0.8rem;
    margin-left: 0.8rem;

    z-index: -1;
}

#container {
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 50rem;
    height: 3rem;
    background-color: rgba(175, 175, 255, 0.2);
    border-radius: 1rem;
}

h4 {
    display: inline-block;

    color: #FFFFFF;
    font-weight: bold;
    z-index: 3;
}

.subMark {
    position: block;

    margin-top: -0.4rem;
    margin-left: 0.3rem;
    width: 100%;
    height: 0.5rem;
    background: linear-gradient(45deg, rgb(0, 92, 230), 60%, rgb(0, 199, 116));
    z-index: 2;
}
</style>

<script>
export default {
    methods: {
        inicio() {
            var inicio = document.getElementById('inicio')
                inicio.scrollIntoView({ behavior: 'smooth' })
        },
        sobreMi() {
            var sobreMi = document.getElementById('sobreMi')
                sobreMi.scrollIntoView({ behavior: 'smooth' })
        },
        titulaciones() {
            var titulaciones = document.getElementById('titulaciones')
            titulaciones.scrollIntoView({ behavior: 'smooth' })
        },
        webDev() {
            var webDev = document.getElementById('webDev')
            webDev.scrollIntoView({ behavior: 'smooth' })
        },
        redes() {
            var redes = document.getElementById('redes')
            redes.scrollIntoView({ behavior: 'smooth' })
        },
        pentesting() {
            var pentesting = document.getElementById('pentesting')
            pentesting.scrollIntoView({ behavior: 'smooth' })
        },
        contacto() {
            var contacto = document.getElementById('contacto')
            contacto.scrollIntoView({ behavior: 'smooth' })
        }
    }
}
</script>