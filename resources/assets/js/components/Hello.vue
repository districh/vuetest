<template>
    <div>
        <h1>Hello, LMT!</h1>
        <p class="hello">{{ msg }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            msg: 'This is a Laravel with Vue and Element Demo.'
        }
    }
}
</script>

<style>
.hello {
    font-size: 2em;
}
</style>