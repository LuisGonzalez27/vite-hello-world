<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            titolo: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>
    <header>
        <h1>{{ titolo }}</h1>
    </header>
</template>

<style lang="css">
header {
    width: 100%;
    height: 100px;
    background-color: black;
    padding: 20px;
}

h1 {
    text-align: center;
    color: white;
    text-transform: uppercase;
}
</style>