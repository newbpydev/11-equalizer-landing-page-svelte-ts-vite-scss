<!-- * SCRIPT -->
<script lang="ts">
  import Button from "./UI/Button.svelte";
</script>

<!-- * TEMPLATE -->
<template>
  <section class="offer">
    <h2 class="offer__heading">Premium EQ</h2>

    <p class="offer__description">
      Get expert-level control with a robust equalizer, volume mixer, and
      spatial audio. Take your listening experience to a whole new level and
      access all our incredible features!
    </p>

    <div class="offer__payment-options">
      <span class="offer__price">$4</span>
      <span class="offer__per-month">/ month</span>
    </div>
    <!-- buttons -->

    <div class="offer__buttons">
      <Button icon="ios">iOS Download</Button>
      <Button icon="android">Android Download</Button>
    </div>
  </section>
</template>

<!-- * STYLE -->
<style lang="scss">
  .offer {
    position: absolute;
    top: 38rem;

    padding: 4.8rem 3.65rem;
    background: var(--orange);
    border-radius: 1.2rem;
    color: var(--white);

    @media screen and (min-width: 25em) {
      padding: 4.8rem;
      width: 40rem;
      left: 50%;
      transform: translateX(-50%);
    }

    @media screen and (min-width: 48em) {
      top: 14.9rem;
      left: 62.5%;
    }

    &__heading {
      font-size: 3.2rem;
      font-weight: 700;
      line-height: 4rem;
      margin-bottom: 1.2rem;
    }

    &__description {
      font-size: 1.8rem;
      line-height: 2.8rem;
      margin-bottom: 3.6rem;
    }

    &__payment-options {
      display: flex;
      align-items: center;
      margin-bottom: 3.2rem;
      margin-left: 0.6rem;

      & .offer__price {
        font-size: 6.5rem;
        font-weight: 700;
        line-height: 5.2rem;
        margin-right: 1.6rem;
      }

      & .offer__per-month {
        font-size: 2rem;
        line-height: 3.2rem;
        letter-spacing: -0.2px;
      }
    }

    &__buttons {
      display: flex;
      flex-direction: column;
      gap: 1.6rem;
      margin-left: 0.6rem;
    }
  }
</style>
