<template lang="">
  <div>
    <div>
      <Navbar></Navbar>
    </div>
    <div>
      <MainCard></MainCard>
    </div>
  </div>
</template>
<script>
import Navbar from '~/components/Navigation.vue'
import MainCard from '~/components/MainCard.vue'
export default {

  components: {
    Navbar,
    MainCard
  }

}
</script>
<style lang="">
    
</style>