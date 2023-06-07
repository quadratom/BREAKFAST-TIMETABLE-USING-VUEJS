<template>
  <div class="container">
    <Header title="MR BEN BREAKFAST RECORD"/>
  </div>
</template>

<script>

import Header from './components/Header.vue'

export default {
  name: 'App',
  components: { Header },
}


</script>

<style>

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif ;
}

.container {
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
  
}

/* .container Header {
  font-size: small;
} */

.btn {
  display: inline-block;
  background: #000;
  color: #fff;
  border: none;
  padding: 10px 29px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}

.btn:focus {
  outline: none;
}

.btn:active {
  transform: scale(0.98);
}

.btn-block {
  display: block;
  width: 100%;
}
</style>