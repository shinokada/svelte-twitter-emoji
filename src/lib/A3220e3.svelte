<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '32 20e3';
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
    d="M23.086 24.907c1.365 0 2.42.62 2.42 2.046 0 1.427-1.055 2.047-2.233 2.047H12.917c-1.364 0-2.418-.62-2.418-2.047 0-.65.403-1.209.713-1.581 2.573-3.069 5.364-5.86 7.721-9.271.558-.806 1.085-1.768 1.085-2.884 0-1.271-.961-2.387-2.233-2.387-3.566 0-1.86 5.023-4.837 5.023-1.488 0-2.264-1.054-2.264-2.264 0-3.906 3.473-7.038 7.287-7.038 3.815 0 6.883 2.512 6.883 6.449 0 4.309-4.805 8.589-7.441 11.906h5.673z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '32 20e3';
-->
