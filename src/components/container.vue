<script>

</script>

<template>
    <div id="contentContainer">
        <slot></slot>
    </div>
</template>

<style>
#contentContainer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    border-radius: 0.5rem;
    padding: 1rem 2rem;
    background-color: rgba(175, 175, 255, 0.1);
    margin: 0.5rem;
    text-align: justify;
}
</style>