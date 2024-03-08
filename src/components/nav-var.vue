<script>

</script>

<template>
    <div id="nav-var">
        <div id="container">
            <h4>inicio<div class="subMark"></div></h4>
            <h4>Sobre mí<div class="subMark"></div></h4>
            <h4>Titulaciones<div class="subMark"></div></h4>
            <h4>Conocimientos<div class="subMark"></div></h4>
            <h4>Contacto<div class="subMark"></div></h4>
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

    width: 100%;
    height: 5rem;

    z-index: 1;
}

#background {
    position: absolute;
    background-color: rgba(185, 185, 255, 0.08);
    width: 40rem;
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
    width: 40rem;
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