<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ea';
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
    fill="#3B88C3"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M12.219 9.621c0-1.55.775-2.697 2.418-2.697h7.689c1.488 0 2.202 1.054 2.202 2.14 0 1.054-.744 2.139-2.202 2.139H16.87v4.527h5.085c1.52 0 2.264 1.054 2.264 2.14 0 1.054-.775 2.139-2.264 2.139H16.87v4.713h5.736c1.488 0 2.201 1.055 2.201 2.14 0 1.055-.744 2.14-2.201 2.14h-7.999c-1.364 0-2.387-.93-2.387-2.325V9.621z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ea';
-->
