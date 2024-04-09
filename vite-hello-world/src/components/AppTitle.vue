<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'La mia prima app con Vue!',
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style scoped>
h1 {
    color: orange;
}
</style>