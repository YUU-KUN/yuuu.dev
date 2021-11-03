<template>
  <div class="hello">
    <div style="font-size: 60px; margin-top: 2%;">{{msg}}</div>
    <p>
      Y-yeah. . .<br>
      This is it. My Portfolio Website.
    </p>
    <ul style="margin: 3% 0">
      <li><a href="https://github.com/YUU-KUN" target="_blank" rel="noopener">Github</a></li>
      <li><a href="https://www.linkedin.com/in/indra-wahyu-577185194" target="_blank" rel="noopener">LinkedIn</a></li>
      <li><a href="mailto:iwahyu809@gmail.com" target="_blank" rel="noopener">Email</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul li {
  margin: 0 2em;
}
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
