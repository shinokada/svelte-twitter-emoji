<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '2198';
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
    d="M0 4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4z"
  /><path fill="#FFF" d="M27 11v16H11z" /><path
    fill="#FFF"
    d="M7 12.657L12.658 7l13.814 13.814-5.656 5.657z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '2198';
-->
