<template>
    <div class="HelloWorld">
        <h1>Hello World!</h1>
        <p>This is your Vue webpack starter application.</p>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld'
}
</script>

<style scoped>
.HelloWorld {
    border: 1px #ddd solid;
    border-radius: 3px;
    text-align: center;
    font-weight: normal;
    font-size:150%;
    padding: 1em;
    margin: auto;
    max-width: 800px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #fff;
}
.HelloWorld h1{
    font-weight: normal;
    margin: 0;
}
</style>