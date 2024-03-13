<script>
import cisco from "../assets/logos/cisco.svg"
import linux from "../assets/logos/linux.svg"
import windows from "../assets/logos/windows.svg"
import mysql from "../assets/logos/mysql.svg"
import mongodb from "../assets/logos/mongo.svg"
import oracle from "../assets/logos/oracle.svg"

export default {
    data() {
        return {
            title1: "Redes",
            text1: "En el ambito de las redes y sistemas tengo buen manejo, sobre todo en sistemas ya que tengo una buena base en GNU/Linux. Y en redes he recibido una buena formacion de Cisco.",
            logo1: cisco,
            logo2: linux,
            logo3: windows,

            title2: "Database",
            text2: "Mysql es la base de datos con la que mas estoy familiarizado pero tambien se usar oracle. Tambien me va bien con MongoDb ya que  utiliza Js, lenguaje el cual estoy desarroyando mucho.",
            logo4: mysql,
            logo5: mongodb,
            logo6: oracle
        }
    }
}
</script>

<template>
    <section class="all-screen flex-around">
        <article class="bordered-and-grey standard-padding small-max" id="article-1-of-networks">
            <h2 class="blue-green-color-text centered big">{{ title1 }}</h2>
            <p class="standard-text">{{ text1 }}</p>
            <picture class="flex-around left-right-min-margin">
                <label class="centered column standard-text"><img class="logos" :src="logo1">Cisco</label>
                <label class="centered column standard-text"><img class="logos" :src="logo2">Linux</label>
                <label class="centered column standard-text"><img class="logos" :src="logo3">Windows</label>
            </picture>
        </article>
        <article class="bordered-and-grey standard-padding small-max" id="article-2-of-networks">
            <h2 class="blue-green-color-text centered big">{{ title2 }}</h2>
            <p class="standard-text">{{ text2 }}</p>
            <picture class="flex-around left-right-min-margin">
                <label class="centered column standard-text"><img class="logos" :src="logo4">MySQL</label>
                <label class="centered column standard-text"><img class="logos" :src="logo5">MongoDB</label>
                <label class="centered column standard-text"><img class="logos" :src="logo6">Oracle</label>
            </picture>
        </article>
    </section>
</template>

<style>

#article-1-of-networks {
    margin-left: 5%;
}

#article-2-of-networks {
    margin-right: 5%;
}

</style>