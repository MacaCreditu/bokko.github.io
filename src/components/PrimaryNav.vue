<template>
  <div>
    <ul>
      <li>Home</li>
      <li>Men</li>
      <li>Women</li>
      <li>Tanks</li>
      <li>Hoddies</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'PrimaryNav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
