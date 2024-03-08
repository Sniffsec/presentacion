<script>

</script>

<template>
    <div id="nav-var">
        <ul>
            <li>Inicio</li>
            <li>Sobre mí</li>
            <li>Titulaciones</li>
            <li>Conocimientos</li>
            <li>Contacto</li>
        </ul>
    </div>
</template>

<style lang="scss">
#nav-var {
    display: flex;
    justify-content: center;
    align-items: center;

    width: 100%;
    height: 5rem;
}

ul {
    display: flex;
    align-items: center;
    justify-content: space-around;

    list-style: none;
    background-color: blue;
    width: 40rem;
    height: 3rem;
    border-radius: 1rem;
    box-shadow: 6px 6px 0px rgb(31, 240, 240);
}

li {
    color: white;
    font-weight: bold;
    text-shadow: 3px 3px 15px rgb(0, 0, 0);
}
</style>