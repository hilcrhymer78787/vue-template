<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/page1">Page1</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  padding: 30px;
}
.wrap {
  border: 3px solid black;
  padding: 20px;
  margin-top: 20px;
}
h2 {
  display: block;
  font-size: 30px;
  font-weight: bold;
  margin: 20px 0;
}
li {
  margin-bottom: 5px;
  list-style: none;
}
pre {
  margin: 0;
}
p {
  margin: 0;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: 0 auto;
}

.wrap {
  border: 3px solid black;
  padding: 20px;
}

.goal .wrap {
  border: 3px solid #42b983;
  margin-bottom: 50px;
  min-height: 300px;
}

.goal h2 {
  color: #42b983;
}

.border {
  margin-bottom: 5px !important;
}

.border_txt {
  opacity: 0.75;
}

.question_txt {
  font-size: 18px;
  margin: 0;
}

.answer_btn {
  margin-bottom: 10px;
}

.attention {
  color: red;
}
#nav {
  margin-bottom: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
