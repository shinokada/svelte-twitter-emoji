<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4c3';
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
    fill="#CCD6DD"
    d="M28 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.875-4-8V4c0-2.209 1.791-4 4-4h20c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#E1E8ED"
    d="M31 36H4c4 0 4-8 4-8 0-2.209 1.791-4 4-4h20c2.209 0 4 2 4 4 0 0 .25 8-5 8z"
  /><path
    fill="#99AAB5"
    d="M24 7c0 .552-.447 1-1 1H5c-.552 0-1-.448-1-1s.448-1 1-1h18c.553 0 1 .448 1 1zm0 4c0 .552-.447 1-1 1H5c-.552 0-1-.448-1-1s.448-1 1-1h18c.553 0 1 .448 1 1zm0 4c0 .552-.447 1-1 1H5c-.552 0-1-.448-1-1s.448-1 1-1h18c.553 0 1 .448 1 1zm0 4c0 .553-.447 1-1 1H5c-.552 0-1-.447-1-1 0-.553.448-1 1-1h18c.553 0 1 .447 1 1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4c3';
-->
