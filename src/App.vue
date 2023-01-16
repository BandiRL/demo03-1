<script>

</script>

<template>
  <div class = "menubar">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to = "/about">About</RouterLink>
    <RouterLink to = "/demo">demo</RouterLink>
    <RouterView />
 
  </div>
  
  

</template>

<style scoped>
  .menubar{
    display: flex;
    flex-direction: row;
    gap: 1em;
  }
</style>
