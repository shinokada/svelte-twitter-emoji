<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f0 1f1fc';
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
  ><path fill="#007A3D" d="M32 5H4C1.791 5 0 6.791 0 9v4.5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#CE1126"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-4.5H0V27z"
  /><path fill="#EEE" d="M0 13.5h36v9H0z" /><path
    fill="#141414"
    d="M1.205 6.138C.462 6.865 0 7.879 0 9v18c0 1.122.462 2.135 1.205 2.862L9 22.5v-9L1.205 6.138z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f0 1f1fc';
-->
