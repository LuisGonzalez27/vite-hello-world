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
    height: 80vh;
    background-image: url(./images/vite.jpg);
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
    font-size: 50px;
}
</style>