<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e7 1f1ec';
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
  ><path fill="#EEE" d="M32 5H4C1.791 5 0 6.791 0 9v5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#D62612"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-5H0v5z"
  /><path fill="#00966E" d="M0 14h36v8H0z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e7 1f1ec';
-->
