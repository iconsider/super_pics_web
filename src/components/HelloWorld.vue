<template>
  <div class="hello">
    <img
      width="350"
      src="https://github.com/lindelof/particles-bg-vue/raw/master/images/logo.png?raw=true"
    >
    <h1>A vue.js particles animation background component</h1>
    <h3>Installed this library</h3>
    <ul>
      <li>
        <a
          href="https://github.com/lindelof/particles-bg-vue"
          target="_blank"
          rel="noopener"
        >vue version</a>
      </li>
      <li>
        <a
          href="https://github.com/lindelof/particles-bg"
          target="_blank"
          rel="noopener"
        >react version</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
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
.hello {
  margin: 0 auto;
  background-color: rgba(0, 0, 0, 0.35);
  padding: 20px 20px;
  border-radius: 8px;
  max-width: 600px;
}
</style>
