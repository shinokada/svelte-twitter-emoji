<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3a4';
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
  ><path
    fill="#8899A6"
    d="M35.999 11.917c0 3.803-3.082 6.885-6.885 6.885-3.802 0-6.884-3.082-6.884-6.885 0-3.802 3.082-6.884 6.884-6.884 3.803 0 6.885 3.082 6.885 6.884z"
  /><path
    fill="#31373D"
    d="M32.81 18.568c-.336.336-.881.336-1.217 0L22.466 9.44c-.336-.336-.336-.881 0-1.217l1.217-1.217c.336-.336.881-.336 1.217 0l9.127 9.128c.336.336.336.881 0 1.217l-1.217 1.217zm-6.071.136l-4.325-4.327c-.778-.779-1.995-.733-2.719.101l-9.158 10.574c-1.219 1.408-1.461 3.354-.711 4.73l-4.911 4.912 1.409 1.409 4.877-4.877c1.381.84 3.411.609 4.862-.648l10.575-9.157c.834-.723.881-1.94.101-2.717z"
  /><path
    fill="#55ACEE"
    d="M4 6v8.122C3.686 14.047 3.352 14 3 14c-1.657 0-3 .896-3 2s1.343 2 3 2 3-.896 3-2V9.889l5 2.222v5.011c-.314-.075-.648-.122-1-.122-1.657 0-3 .896-3 2s1.343 2 3 2 2.999-.896 3-2v-9L4 6zm14-5v8.123C17.685 9.048 17.353 9 17 9c-1.657 0-3 .895-3 2 0 1.104 1.343 2 3 2 1.656 0 3-.896 3-2V1h-2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3a4';
-->
