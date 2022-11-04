<!-- * SCRIPT -->
<script lang="ts">
</script>

<!-- * TEMPLATE -->
<template>
  <section class="hero wrapper">
    <h1 class="hero__title">We make your music sound extraordinary.</h1>

    <p class="hero__description">
      A system audio equalizer specifically designed for Android and iOS. Freely
      tune the way your music sounds with a professional grade parametric EQ &
      volume mixer. Control bass, mids, treble, gain control, reverb, and more!
    </p>
  </section>
</template>

<!-- * STYLE -->
<style lang="scss">
  .hero {
    margin-bottom: 16.6rem;

    @media screen and (min-width: 48em) {
      margin-bottom: 25rem;
    }

    & .hero__title {
      font-size: 4rem;
      line-height: 4.8rem;
      font-weight: 700;
      letter-spacing: -0.45px;
      margin-bottom: 2rem;

      @media screen and (min-width: 48em) {
        font-size: 6.4rem;
        width: 52rem;
        line-height: 6.4rem;
        letter-spacing: -0.7272px;
        margin-bottom: 2.8rem;
      }

      @media screen and (min-width: 68.75em) {
        font-size: 8.8rem;
        line-height: 8.8rem;
        width: 101.5rem;
        letter-spacing: -1px;
        margin-bottom: 4rem;
      }
    }

    & .hero__description {
      line-height: 2.6rem;

      @media screen and (min-width: 48em) {
        font-size: 1.8rem;
        width: 51.4rem;
        line-height: 2.8rem;
      }

      @media screen and (min-width: 68.75em) {
        font-size: 2rem;
        width: 82.5rem;
        line-height: 3.4rem;
      }
    }
  }
</style>
