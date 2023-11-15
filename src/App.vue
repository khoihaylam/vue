<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <h1>HelloWorld</h1>
  <h3>xin chào các bạn</h3>
  <div class="container">
    <p>alo</p>
    <span>các bạn vui lòng lưu lý</span>
  </div>
  <form>
    <input type="text" /><br />
    <input type="number" />
    <input type="number" />
  </form>
  <div class="ok">hi các bạn</div>
  <div class="grid grid-rows-3 grid-flow-col gap-4">
    <div class="row-start-2 row-span-2 ...">01</div>
    <div class="row-end-3 row-span-2 ...">02</div>
    <div class="row-start-1 row-end-4 ...">03</div>
  </div>
  <section>
    <div class="ol">
      <p>23</p>
    </div>
  </section>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container {
  color: aqua;
}
.ok:hover {
  width: 300px;
  height: 200px;
  background-color: aqua;
  border: 0;
  border-radius: 50%;
  padding: 25px;
}
.ol{
  color: wheat;
}
</style>
