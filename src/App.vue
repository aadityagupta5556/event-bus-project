<template>
  <div>
    <one-tag></one-tag>
    <eight-tag></eight-tag>
  </div>
</template>

<script>
import One from './components/One.vue'
import Eight from './components/Eight.vue'
export default {
  name: 'App',
  components: {
    'one-tag': One,
    'eight-tag': Eight
  }

}
</script>

<style>

</style>