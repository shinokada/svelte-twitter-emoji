<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f2 1f1fa';
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
  ><path fill="#EA2839" d="M32 5H4C1.791 5 0 6.791 0 9v2.5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#1A206D"
    d="M0 11.5h36V18H0z"
  /><path fill="#FFD500" d="M0 18h36v6.5H0z" /><path
    fill="#00A551"
    d="M0 24.5V27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-2.5H0z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f2 1f1fa';
-->
