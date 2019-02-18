<template>
  <h1>{{msg}}</h1>
</template>

<script>
  export default {
    name: 'App',
    data: function () {
        return {
            msg: 'Hello World'
        }
    }
  }
</script>

<style lang="sass">
    h1 {
        color: red;
    }
</style>


