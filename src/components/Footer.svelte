<!-- * SCRIPT -->
<script lang="ts">
  import logo from "../assets/images/logo.svg";
  import facebook from "../assets/images/icon-facebook.svg";
  import instagram from "../assets/images/icon-instagram.svg";
  import twitter from "../assets/images/icon-twitter.svg";
</script>

<!-- * TEMPLATE -->
<template>
  <footer class="footer wrapper">
    <img src={logo} alt="equalizer logo" class="footer__logo" />

    <div class="footer__social-copy-wrapper">
      <div>
        <p class="footer__copyright">All rights reserved © Equalizer 2021</p>
        <p class="footer__contact">
          Have any problems? Contact us via social media or email us at
          <span class="footer__email">equalizer@example.com </span>
        </p>
      </div>

      <div class="footer__social">
        <a href="#" class="footer__icon-facebook">
          <img src={facebook} alt="facebook link" />
        </a>
        <a href="#" class="footer__icon-instagram">
          <img src={instagram} alt="instagram link" />
        </a>
        <a href="#" class="footer__icon-twitter">
          <img src={twitter} alt="twitter link" />
        </a>
      </div>
    </div>
  </footer>
</template>

<!-- * STYLE -->
<style lang="scss">
  .footer {
    display: flex;
    flex-direction: column;
    gap: 3.2rem;
    margin-bottom: 8rem;

    &__social-copy-wrapper {
      display: flex;
      flex-direction: column;
      gap: 6.4rem;
    }
    &__logo {
      width: 14.6rem;
    }

    &__copyright,
    &__contact {
      line-height: 2.6rem;
      // width: 31.7rem;
    }

    &__email {
      font-weight: 700;
    }

    &__social {
      display: flex;
      gap: 2rem;
      align-items: center;

      & img {
        width: 2rem;
      }
    }
  }
</style>
