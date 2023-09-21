<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4c1';
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
    d="M0 29c0 2.209 1.791 4 4 4h24c2.209 0 4-1.791 4-4V12c0-2.209-1.791-4-4-4h-9c-3.562 0-3-5-8.438-5H4C1.791 3 0 4.791 0 7v22z"
  /><path
    fill="#55ACEE"
    d="M30 10h-6.562C18 10 18.562 15 15 15H6c-2.209 0-4 1.791-4 4v10c0 .553-.448 1-1 1s-1-.447-1-1c0 2.209 1.791 4 4 4h26c2.209 0 4-1.791 4-4V14c0-2.209-1.791-4-4-4z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4c1';
-->
