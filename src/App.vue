<script>
import AppTitle from './components/AppTitle.vue'
import AppFoto from './components/AppFoto.vue'


export default{
  components: {
    AppTitle,
    AppFoto
  }
}
</script>



<template>
<h1>Ciao Mondo</h1>

<AppTitle/>
<AppFoto/>

</template>


<style>
h1{
  color: red;
}
</style>
