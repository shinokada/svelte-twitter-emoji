<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f683';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  {...$$restProps}
  {role}
  aria-label={ariaLabel}
  on:click
  on:keydown
  on:keyup
  on:focus
  on:blur
  on:mouseenter
  on:mouseleave
  on:mouseover
  on:mouseout
  viewBox="0 0 36 36"
  ><path fill="#939598" d="M0 34h36v2H0z" /><path
    fill="#58595B"
    d="M8 32c0-1.657-1.344-3-3-3s-3 1.343-3 3 1.343 3 3 3 3-1.343 3-3z"
  /><path fill="#292F33" d="M7 32c0-1.105-.896-2-2-2s-2 .895-2 2 .896 2 2 2 2-.895 2-2z" /><path
    fill="#58595B"
    d="M16 32c0-1.657-1.344-3-3-3s-3 1.343-3 3 1.343 3 3 3 3-1.343 3-3z"
  /><path fill="#292F33" d="M15 32c0-1.105-.896-2-2-2s-2 .895-2 2 .896 2 2 2 2-.895 2-2z" /><circle
    fill="#58595B"
    cx="32"
    cy="32"
    r="3"
  /><circle fill="#292F33" cx="32" cy="32" r="2" /><circle
    fill="#58595B"
    cx="24"
    cy="32"
    r="3"
  /><circle fill="#292F33" cx="24" cy="32" r="2" /><path fill="#5C913B" d="M0 28h36v4H0z" /><path
    fill="#FFE8B6"
    d="M0 16h36v12H0z"
  /><path fill="#FFAC33" d="M0 26h36v2H0z" /><path
    fill="#77B255"
    d="M32.555 14H3.445C1.969 14 .693 14.81 0 16h36c-.693-1.19-1.969-2-3.445-2z"
  /><path
    d="M5 22c0 .553-.447 1-1 1H2c-.552 0-1-.447-1-1v-2c0-.553.448-1 1-1h2c.553 0 1 .447 1 1v2zm6 0c0 .553-.447 1-1 1H8c-.552 0-1-.447-1-1v-2c0-.553.448-1 1-1h2c.553 0 1 .447 1 1v2zm6 0c0 .553-.447 1-1 1h-2c-.553 0-1-.447-1-1v-2c0-.553.447-1 1-1h2c.553 0 1 .447 1 1v2zm6 0c0 .553-.447 1-1 1h-2c-.553 0-1-.447-1-1v-2c0-.553.447-1 1-1h2c.553 0 1 .447 1 1v2zm6 0c0 .553-.447 1-1 1h-2c-.553 0-1-.447-1-1v-2c0-.553.447-1 1-1h2c.553 0 1 .447 1 1v2zm6 0c0 .553-.447 1-1 1h-2c-.553 0-1-.447-1-1v-2c0-.553.447-1 1-1h2c.553 0 1 .447 1 1v2z"
    fill="#55ACEE"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f683';
-->
