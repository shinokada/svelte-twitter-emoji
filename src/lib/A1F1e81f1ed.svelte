<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e8 1f1ed';
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
    fill="#D32D27"
    d="M31 27c0 2.209-1.791 4-4 4H9c-2.209 0-4-1.791-4-4V9c0-2.209 1.791-4 4-4h18c2.209 0 4 1.791 4 4v18z"
  /><path fill="#FFF" d="M25 16.063h-5v-5h-4v5h-5V20h5v5.063h4V20h5z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e8 1f1ed';
-->
