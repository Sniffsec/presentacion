<script>
import stars from "../assets/media/estrella.svg"

export default {
    data() {
        return {
            stars: stars,
            title: "Titulaciones",
            qualification1: {
                name: "Educacion Secundaria",
                center: "(Centro Uribe-Kosta BHI)",
                date: "2018-2021"
            },
            qualification2: {
                name: "Técnico en Preimpresión Digital",
                center: "(Centro Emilio Campuzano)",
                date: "2021-2023"
            },
            qualification3: {
                name: "Técnico en ASIR",
                center: "(Centro Almi)",
                date: "2023-Actualidad"
            },
            subtitle: "Idiomas",
            lenguage1: {
                name: "Inglés",
                qualification: "B1",
                text: "(Sin título pero en proceso de obtencion del B2)"
            },
            lenguage2: {
                name: "Euskara",
                qualification: "B2",
                text: "(Titulación de HABE)"
            }
        }
    }
}

</script>

<template>
    <section class="all-screen centered column">
        <h2 class="blue-green-color-text centered big"><img class="stars2" :src="stars" alt="">{{ title }}</h2>
        <article class="bordered-and-grey standard-padding standard-max margin-top centered">
            <div id="margin-right-for-qualifications">
                <div class="text-without-margin">{{ qualification1.name }}</div>
                <div class="standard-text">{{ qualification2.name }}</div>
                <div class="standard-text">{{ qualification3.name }}</div>
            </div>
            <div id="margin-both-for-qualifications">
                <div class="text-without-margin">{{ qualification1.center }}</div>
                <div class="standard-text">{{ qualification2.center }}</div>
                <div class="standard-text">{{ qualification3.center }}</div>
            </div>
            <div id="margin-left-for-qualifications">
                <div class="text-without-margin">{{ qualification1.date }}</div>
                <div class="standard-text">{{ qualification2.date }}</div>
                <div class="standard-text">{{ qualification3.date }}</div>
            </div>
        </article>
        <h2 class="blue-green-color-text medium margin-top">{{ subtitle }}</h2>
        <article class="bordered-and-grey standard-padding standard-max margin-top centered">
            <div id="margin-right-for-qualifications">
                <div class="text-without-margin">{{ lenguage1.name }}</div>
                <div class="standard-text">{{ lenguage2.name }}</div>
            </div>
            <div id="margin-both-for-qualifications">
                <div class="text-without-margin">{{ lenguage1.qualification }}</div>
                <div class="standard-text">{{ lenguage2.qualification }}</div>
            </div>
            <div id="margin-both-for-qualifications">
                <div class="text-without-margin">{{ lenguage1.text }}</div>
                <div class="standard-text">{{ lenguage2.text }}</div>
            </div>
        </article>
    </section>
</template>

<style>

#margin-right-for-qualifications {
    margin-right: 2rem;
}

#margin-both-for-qualifications {
    margin: 0 2rem;
}

#margin-left-for-qualifications {
    margin-left: 2rem;
}

</style>