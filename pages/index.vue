<template>
  <div>
    {{counter}}
  </div>
</template>

<script>
  import {mapState} from 'vuex'
  computed:{
      ...mapState({
          counter:state => state.counter
      })
  }
</script>
