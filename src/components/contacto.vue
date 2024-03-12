<script>

export default {
    data() {
        return {
            title: "Contacto",
            mail: "sniffsec@proton.me",
            github: "Sniffsec",
            linkedin: "Álex Frías Angulo"
        }
    }
}

</script>

<template>
    <section class="all-screen centered column">
        <h2 class="blue-green-color-text centered big">{{ title }}</h2>
        <div class="bordered-and-grey standard-padding centered wrap small-max">
            <h2 class="text-without-margin bordered-and-purple-gradient min-padding centered min-column-margin">Mail</h2>
                <label class="text-without-margin flex-wrap">{{ mail }}</label>
            <h2 class="text-without-margin bordered-and-purple-gradient min-padding centered min-column-margin">Github</h2>
                <label class="text-without-margin flex-wrap">{{ github }}</label>
            <h2 class="text-without-margin bordered-and-purple-gradient min-padding centered min-column-margin">Linkedin</h2>
                <label class="text-without-margin flex-wrap">{{ linkedin }}</label>
        </div>
    </section>    
</template>

<style>

</style>