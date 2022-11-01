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
    margin-top: 2.415rem;
    margin-bottom: 6.4rem;

    & .header__logo {
      width: 14.6rem;
    }
  }
</style>
