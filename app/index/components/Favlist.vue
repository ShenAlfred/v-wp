<template>
    <div>
        <div v-for="n in 10">{{ msg }}</div>
    </div>
</template>

<script>
    export default {
        data () {
            return {
                msg: 'Hello World!'
            }
        }
    }
</script>

<style>
    html{
        background: #ccc;
        font-size: 24px;
    }
</style>