<template>
  <section>
    <div class="hero">
      <h1>...world! This is a test landing page.</h1>
      <p>
        This is some placeholder text, it doesnt mean anything at all, just
        doesn't feel like using lorem ipsum today.
      </p>
      <button class="primary">Call to action</button>
    </div>
    <div class="img">
      <a
        class="source"
        href="https://www.pexels.com/es-es/@juan-nino-3824481"
        target="_blank"
        >🔗
      </a>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  width: 80%;
  height: 85vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: auto;
}
section .hero {
  width: 35%;
}
section .hero h1 {
  font-size: 3rem;
  line-height: 2.75rem;
}
section .hero * {
  margin: 0 0 2rem 0;
}
section div.img {
  position: relative;
  width: 60%;
  height: 70vh;
  border-radius: 1rem;
  background-image: url("../assets/pexels-juan-nino-9556451(1).jpg");
  background-size: cover;
}
section div.img .source {
  position: absolute;
  right: 0;
  bottom: 0;
  padding: 1rem;
  background-color: #000;
  opacity: 0.7;
  text-decoration: none;
  margin: 1rem;
  border-radius: 0.5rem;
}
section div.img .source:hover {
  transition: 0.25s;
  opacity: 1;
}
</style>