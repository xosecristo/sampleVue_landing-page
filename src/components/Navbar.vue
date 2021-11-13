<template>
  <header>
    <a href="#" id="logo">Hello.</a>
    <nav>
      <ul>
        <li class="here"><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Work</a></li>
        <button class="secondary">Action</button>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  color: inherit;
  text-decoration: none;
}
header {
  /* FEEL */
  width: 80%;
  min-height: 10vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: auto;
  /* LOOK */
  font-size: 1rem;
}
header #logo {
  font-size: 2.5rem;
  font-weight: 700;
  color: blueviolet;
}
nav ul {
  display: flex;
  align-items: center;
  list-style: none;
}
nav ul li {
  margin-right: 1.5rem;
  font-weight: 400;
}
nav ul li.here {
  font-weight: 500;
}
</style>