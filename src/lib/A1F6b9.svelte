<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6b9';
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
    fill="#FFF"
    d="M26.795 15.727l-7.041-4.4C20.506 10.691 21 9.666 21 8.5 21 6.566 19.656 5 18 5c-1.657 0-3 1.567-3 3.5 0 1.166.494 2.192 1.246 2.828l-7.041 4.4c-.703.439-.916 1.364-.477 2.067.439.703 1.364.916 2.067.477L14 16.268V31.5c0 .828.671 1.5 1.5 1.5s1.5-.672 1.5-1.5V24c0-.553.448-1 1-1s1 .447 1 1v7.5c0 .828.672 1.5 1.5 1.5s1.5-.672 1.5-1.5V16.269l3.205 2.003c.247.155.522.228.794.228.5 0 .988-.25 1.273-.705.439-.703.225-1.628-.477-2.068z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6b9';
-->
