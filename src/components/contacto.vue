<script>
import copy from "../assets/media/copy.svg"

export default {
    data() {
        return {
            title: "Contacto",
            mail: "sniffsec@proton.me",
            github: "Sniffsec",
            linkedin: "Álex Frías Angulo",
            copy: copy
        }
    }
}

</script>

<template>
    <section class="all-screen centered column">
        <h2 class="blue-green-color-text centered big">{{ title }}</h2>
        <div class="bordered-and-grey standard-padding small-max">
            
            <div class="flex-alighned">
                <h3 class="text-without-margin bordered-and-purple-gradient min-padding centered min-column-margin">Mail</h3>
                <label class="text-without-margin">{{ mail }}</label>
                <img :src="copy" alt="copy" class="copy">
            </div>

            <div class="flex-alighned">
                <h3 class="text-without-margin bordered-and-purple-gradient min-padding centered min-column-margin">Linkedin</h3>
                <label class="text-without-margin">{{ linkedin }}</label>
                <img :src="copy" alt="copy" class="copy">
            </div>

            <div class="flex-alighned">
                <h3 class="text-without-margin bordered-and-purple-gradient min-padding centered min-column-margin">Github</h3>
                <label class="text-without-margin">{{ github }}</label>
                <img :src="copy" alt="copy" class="copy">
            </div>
            
        </div>
    </section>    
</template>

<style>

</style>