<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f5 1f1f8';
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
  ><path fill="#141414" d="M32 5H4C1.791 5 0 6.791 0 9v4.5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#007229"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-4.5H0V27z"
  /><path fill="#EEE" d="M0 13.5h36v9H0z" /><path
    fill="#D21034"
    d="M1.351 6.004H1.35C.522 6.737 0 7.808 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18 1.351 6.004z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f5 1f1f8';
-->
