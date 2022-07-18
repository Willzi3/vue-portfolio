<template>
  <div id="Landing">
    <h1>Zachary Williams</h1>
    <p>Aspiring Full-Stack Developer</p>
  </div>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
#Landing{
  height: 100vh;
  border: 1px solid black;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background-image: url(../assets/bg.jpg);
  background-attachment: fixed;
}




</style>
