<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1fb 1f1e8';
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
  ><path fill="#009E60" d="M32 5h-5v26h5c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z" /><path
    fill="#0072C6"
    d="M4 5C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h5V5H4z"
  /><path fill="#FCD116" d="M9 5h18v26H9z" /><path
    d="M15.833 23.526L18 27.859l2.167-4.333L18 19.193l-2.167 4.333zm-2.708-5.417l2.167 4.333 2.167-4.333-2.167-4.333-2.167 4.333zm5.417 0l2.167 4.333 2.167-4.333-2.167-4.333-2.167 4.333z"
    fill="#009E60"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1fb 1f1e8';
-->
