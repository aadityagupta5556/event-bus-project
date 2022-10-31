<template>
    <div></div>
</template>
  
<script>

export default {
    name: 'App',
    components: {

    },
    mounted() {
        this.emitter.emit('I-am-child', "It is data from One which is send to Eight")
    },

}
</script>
  
<style>

</style>
  