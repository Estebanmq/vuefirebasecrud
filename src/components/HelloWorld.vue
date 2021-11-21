<template>
  <div class="hello">
    <h1>Esto firestore</h1>
  </div>
</template>

<script>
import ServiceFirebase from "./../services/ServiceFirebase"

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }, data() {
      return {
      

      }
  } , mounted() {
    console.log("Mounted")
    ServiceFirebase.getAll();
  
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
