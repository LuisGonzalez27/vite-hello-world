<script>
export default {
    name: 'AppHero',
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <div class="jumbotron-text">
            <h2>I am Vite</h2>
        </div>
    </div>
</template>

<style lang="css">
.jumbotron {
    width: 100%;
    height: calc(100vh - 100px);
    background-image: url(./images/logo.png);
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
}

.jumbotron-text {
    position: absolute;
    text-align: center;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: black;
    font-size: 25px;
    font-family: 'Press Start 2P', cursive;
}
</style>