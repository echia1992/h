<template>
  <img class="logo" src="./assets/tee-logo.png" />
  <SignUp />
</template>

<script>
import SignUp from "./components/SignUp.vue";
export default {
  name: "App",
  components: {
    SignUp,
  },
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
.logo {
  width: 100px;
}
.signup input {
  width: 300px;
  height: 40px;
  padding-left: 20px;
  margin-bottom: 30px;
  display: block;
  margin-right: auto;
  margin-left: auto;
  margin-top: auto;
  border: 1px solid lightskyblue;
}
.signup button {
  width: 330px;
  background-color: deepskyblue;
  padding: 5px;
  border: none;
  cursor: pointer;
  color: #fff;
}
.signup button:hover {
  color: blueviolet;
}
</style>
