<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6c4';
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
    fill="#269"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#F5F8FA"
    d="M29 8h-2v18h2c1.104 0 2-.896 2-2V10c0-1.104-.896-2-2-2zM7 8c-1.104 0-2 .896-2 2v14c0 1.104.896 2 2 2h2V8H7zm16 0V5c0-1.105-.896-2-2-2h-6c-1.104 0-2 .895-2 2v3h-2v18h14V8h-2zm-8-2c0-.552.448-1 1-1h4c.553 0 1 .448 1 1v2h-6V6zm18 22H3c-.552 0-1 .447-1 1s.448 1 1 1h1c0 1.104.896 2 2 2s2-.896 2-2h2c0 1.104.896 2 2 2s2-.896 2-2h2c0 1.104.896 2 2 2s2-.896 2-2h2c0 1.104.896 2 2 2s2-.896 2-2h2c0 1.104.896 2 2 2s2-.896 2-2h1c.553 0 1-.447 1-1s-.447-1-1-1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6c4';
-->
