<!-- * SCRIPT -->
<script lang="ts">
  import Offer from "./Offer.svelte";
  import Button from "./UI/Button.svelte";
  import illustrationApp from "../assets/images/illustration-app.png";
</script>

<!-- * TEMPLATE -->
<template>
  <section class="offer-section">
    <picture class="offer-section__picture">
      <img
        class="offer-section__image"
        src={illustrationApp}
        alt="an illustration og
      the equalizer app on a mobile phone"
      />
    </picture>

    <Offer />
  </section>
</template>

<!-- * STYLE -->
<style lang="scss">
  .offer-section {
    background: url("../assets/images/bg-pattern-2.svg") var(--black);
    background-size: 28rem;
    background-position: top;
    background-repeat: no-repeat;
    height: 60rem;
    position: relative;
    border-radius: 1.2rem;
    margin-bottom: 39rem;

    &__image {
      position: absolute;
      top: -9.9rem;
      left: 50%;
      transform: translateX(-51%);
      margin: 0 auto;
      width: 20.897rem;
    }
  }
</style>
