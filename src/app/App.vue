<template>
    <div class="App">
        <HelloWorld></HelloWorld>
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
    name: 'App',
    components: {
        HelloWorld
    }
}
</script>

<style scoped>
.App {
    padding: 1em;
}
</style>