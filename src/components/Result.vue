<template>
    <p>Counter is: {{ counterStatus }}</p>
</template>

<script>
  import { mapGetters } from 'vuex'

  export default {
    computed: {
      ...mapGetters([
        'counterStatus'
      ])
    }
  }
</script>