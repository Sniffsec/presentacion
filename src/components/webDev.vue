<script>
import stars from "../assets/media/estrella.svg"
import vue from "../assets/logos/vue.svg"
import js from "../assets/logos/js.svg"
import node from "../assets/logos/nodejs.svg"
import aws from "../assets/logos/aws.svg"

export default {
    data() {
        return {
            stars: stars,
            title: "Web development",
            text: "Este año me he empezado a interesar por el desarrollo web, me parece un área muy interesante en la cual hay infinidad de herramientas con las que se puede hacer el diseño de una página web. A mí siempre me ha gustado el diseño, y al ver que con el desarrollo web podía crear páginas y utilizar mis conocimientos de diseño, me llamó mucho la atención.",
            subtitle: "Tecnologías",
            logo1: vue,
            logo2: js,
            logo3: node,
            logo4: aws,
        }
    }
}
</script>

<template>
    <section class="all-screen centered column">
        <h2 class="blue-green-color-text centered big"><img class="stars2" :src="stars" alt="">{{ title }}</h2>
        <article class="bordered-and-grey standard-padding standard-max margin-top">
            <p class="standard-text centered">{{ text }}</p>
        </article>
            <h2 class="blue-green-color-text medium margin-top">{{ subtitle }}</h2>
            <picture class="flex-around left-right-min-margin">
                <label class="centered column standard-text standard-margin"><img class="logos" :src="logo1">Vue.js</label>
                <label class="centered column standard-text standard-margin"><img class="logos" :src="logo2">Js</label>
                <label class="centered column standard-text standard-margin"><img class="logos" :src="logo3">Node.js</label>
                <label class="centered column standard-tex standard-margin"><img class="logos" :src="logo4">AWS</label>
            </picture>
    </section>
</template>

<style>

</style>