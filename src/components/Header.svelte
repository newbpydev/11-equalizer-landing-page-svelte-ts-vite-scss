<!-- * SCRIPT -->
<script lang="ts">
  import logo from "../assets/images/logo.svg";
</script>

<!-- * TEMPLATE -->
<template>
  <header class="header wrapper">
    <img class="header__logo" src={logo} alt="equalizer logo" />
  </header>
</template>

<!-- * STYLE -->
<style lang="scss">
  .header {
    margin-top: 3.9rem;
    margin-bottom: 6rem;

    @media screen and (min-width: 48em) {
      margin-top: 6.2rem;
      margin-bottom: 9.5rem;
    }

    & .header__logo {
      width: 14.6rem;
    }
  }
</style>
