<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <h3>
      Technology
    </h3>
    <div class="overiglinks">
        <li>
          <ul><b><p>Github:</p></b></ul>
          <ul><a href="https://github.com/alecsiemerink"><p>Alec Siemerink</p></a></ul>
        </li>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
h3 {
  font-family: 'Source Code Pro Light', monospace;
  font-size: 30px;
}
h1 {
  font-family: 'Source Code Pro', monospace;
  font-size: 55px;
}
p {
  font-family: 'Source Code Pro', monospace;
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
  color: #2e7aa3;
}
ul {
  display: inline-block;
  padding: 20px;
}
</style>
