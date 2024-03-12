<template>
    <section id="redes">
        <h2 class="titulo">Redes</h2>
        <div id="contRedes">
            <p class="texto textoRedDb">En el ambito de las redes y sistemas tengo buen manejo, sobre todo en sistemas ya que tengo una buena base en GNU/Linux. Y en redes he recibido una buena formacion de Cisco.</p>
            <label class="tecnologias" for=""><img class="logos" src="../assets/logos/cisco.svg" alt="Cisco">Redes con Cisco</label>
        </div>
        
        <h2 class="titulo">Database</h2>
        <div id="contDb">
            <p class="texto textoRedDb">Mysql es la base de datos con la que mas estoy familiarizado pero tambien se usar oracle. Tambien me va bien con MongoDb ya que  utiliza Js, lenguaje el cual estoy desarroyando mucho.</p>
            <div id="contTecnologias">
                <label class="tecnologias" for=""><img class="logos" src="../assets/logos/mongo.svg" alt="MongoDb">MongoDb</label>
                <label class="tecnologias" for=""><img class="logos" src="../assets/logos/mysql.svg" alt="MySQL">MySQL</label>
                <label class="tecnologias" for=""><img class="logos" src="../assets/logos/oracle.svg" alt="MongoDb">Oracle</label>
            </div>
        </div>
    </section>
</template>

<style>

#redes {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
}

#contRedes {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    width: 30rem;
    padding: 2rem 3rem;
    border-radius: 0.5rem;
    background-color: rgba(175, 175, 255, 0.1);
    margin-bottom: 7rem;
}

#contDb {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    width: 30rem;
    padding: 2rem 3rem;
    border-radius: 0.5rem;
    background-color: rgba(175, 175, 255, 0.1);
    margin-bottom: 7rem;
}

.textoRedDb {
    font-weight: bold;
    text-align: justify;
}

#contTecnologias {
    display: flex;
    justify-content: center;
}

</style>

<script>

</script>