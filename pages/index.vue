<template>    
    <google-map
      name="example"
    ></google-map>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import GoogleMap from '~/components/map.vue'

export default {
  components: {
    AppLogo,
    GoogleMap
  }
}
</script>

<style>
  input {
    display: block;
    margin: 0 auto;
  }

  input:first-child {
    margin-top: 10vh;
  }

  input[type=button] {
    margin: 1vh auto;
  }
</style>

