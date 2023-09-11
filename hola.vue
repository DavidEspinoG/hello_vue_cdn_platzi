<template>
  <div>
    <p>Hola desde un archivo .vue</p>
    <p>{{ text }}</p>
  </div>  
</template>

<script>
  export default {
    data() {
      return {
        text: 'Hola desde la data de .vue'
      }
    }
  };
</script>

<style>
p {
  color: pink;
}

</style>