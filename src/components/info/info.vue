<template>
  <div class="info">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Info',
  data () {
    return {
      msg: 'Info'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
  color: #1f8155;
}
</style>