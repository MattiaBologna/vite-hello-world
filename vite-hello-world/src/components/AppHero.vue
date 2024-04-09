<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'Hero section',
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style scoped>
h1 {
    color: violet;
    background-image: url('images/Dragon_Ball_Super.png');
    width: 100vh;
    height: 100vh;
    background-size: cover;
    background-position: center;
}
</style>