<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f3 1f1f7';
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
    fill="#002B7F"
    d="M36 27c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V9c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v18z"
  /><path fill="#FFC61E" d="M0 17h36v2H0z" /><path
    fill="#FFF"
    d="M9.979 19.479l.492 1.965 1.409-1.456-.556 1.949 1.949-.557-1.457 1.409 1.966.492-1.966.492 1.457 1.41-1.949-.557.556 1.949-1.409-1.457-.492 1.966-.492-1.966-1.409 1.457.556-1.949-1.948.557 1.456-1.41-1.966-.492 1.966-.492-1.456-1.409 1.948.557-.556-1.949 1.409 1.456z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f3 1f1f7';
-->
