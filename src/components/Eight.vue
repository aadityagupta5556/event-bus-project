<template>
    <div>
        <h1>{{ value }}</h1>
    </div>
</template>
  
<script>


export default {
    name: 'App',
    components: {

    },
    data() {
        return {
            value: ''
        }
    },
    created() {
        this.emitter.on('I-am-child', (data) => {
            this.value = data
        })
    },

}
</script>
  
<style>

</style>
  