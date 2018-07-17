<template>
  <div id="home">
    <heades></heades>
    <banner></banner>
  </div>
</template>

<script>
import heades from "../components/heades"
import banner from "../components/banner"
export default {
  name: 'home',
  components:{
    heades,
    banner
  }
 
}
</script>
<style lang="scss" scoped>
 #home{
   width: 100%;
 }

</style>
