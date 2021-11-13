<template>
  <main id="app">
    <Navbar />
    <Home />
    <button id="email">✉</button>
  </main>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Home,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap");
#app {
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: #fff;
}
body {
  background: #000;
}
button {
  border: none;
  font-size: 1.5rem;
  font-weight: 700;

  padding: 0.5rem 1.5rem;
  border-radius: 0.75rem;
  cursor: pointer;
}
button.primary {
  color: #fff;
  background: blueviolet;
}
button.secondary {
  color: blueviolet;
  background: #fff;
  transition: 0.25s;
}
button.secondary:hover {
  color: #fff;
  background: blueviolet;
  transition: 0.25s;
}
button#email {
  position: absolute;
  right: 2rem;
  bottom: 2rem;
  border-radius: 0.5rem;
  font-size: 2.5rem;
  color: #fff;
  background: blueviolet;
}
</style>
