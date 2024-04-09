<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'La mia prima app con Vue!',
            counter: 0,
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
    <button @click="counter++">Counter</button>
    <div>{{ counter }}</div>
</template>

<style scoped>
h1 {
    color: orange;
}
</style>