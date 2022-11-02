<!-- * SCRIPT -->
<script lang="ts">
  import logoApple from "../../assets/images/icon-apple.svg";
  import logoAndroid from "../../assets/images/icon-android.svg";

  // export let text: string = "IOS Download";
  // export let variant: "dark" | "light";
  export let icon: "android" | "ios";
</script>

<!-- * TEMPLATE -->
<template>
  <button class={`button ${icon === "android" ? "light" : "dark"}`}>
    <img
      class="button__icon"
      src={icon === "android" ? logoAndroid : logoApple}
      alt="product logo"
    />
    <slot />
  </button>
</template>

<!-- * STYLE -->
<style lang="scss">
  .button {
    width: 100%;
    // height: 6.1rem;
    padding: 1.5rem 0;
    border-radius: 1.2rem;
    text-align: center;
    font-size: 1.8rem;
    font-weight: 700;
    letter-spacing: -0.18px;
    line-height: 3.2rem;
    cursor: pointer;
    transition: all 0.3s ease;

    &__icon {
      fill: white;
      margin-right: 0.78rem;
    }

    &.dark {
      background: var(--black);
      color: var(--white);

      &:hover {
        background: var(--blue-light);
      }
    }

    &.light {
      background: var(--white);
      color: var(--black);

      &:hover {
        background: var(--yellow);
      }
    }
  }
</style>
