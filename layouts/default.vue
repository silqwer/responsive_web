<template>
  <div id="wrap">
    <TheHeader/>
    <Nuxt/>
    <TheFooter/>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
#wrap{
  display: flex;
  flex-flow: row wrap;
  width: 90%;
  margin: 0 auto;
}
</style>