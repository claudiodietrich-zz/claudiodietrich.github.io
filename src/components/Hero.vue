<template>
  <section class="hero has-text-centered">
    <div class="hero-body">
      <div class="container">
        <h1 class="title is-size-4-mobile is-size-1-desktop">Full-Stack Developer</h1>
        <h2 class="subtitle is-size-5-mobile is-size-4-desktop">I code beautifully simple things, and I love what I do.</h2>
        <img class="is-bottom" src="@/assets/img/avatar.svg" alt="Avatar">
      </div>
    </div>

    <div class="hero-foot">
      <div class="container">
        <img class="is-bottom" src="@/assets/img/hero.png" alt="Hero">
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero-foot img {
  margin-bottom: -0.4rem;
}

@media screen and (min-width: 769px) {
  .hero-foot img {
    margin-bottom: -0.45rem;
    max-width: 860px;
  }
}
</style>

