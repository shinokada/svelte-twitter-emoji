<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1fb';
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
    d="M8.917 10.117C8.762 9.714 8.7 9.404 8.7 8.97c0-1.302 1.147-2.232 2.387-2.232 1.055 0 1.706.682 2.108 1.519l4.806 12.898 4.807-12.898c.402-.837 1.053-1.519 2.107-1.519 1.24 0 2.387.93 2.387 2.232 0 .434-.06.744-.217 1.147l-6.789 17.271c-.404.992-.931 1.798-2.295 1.798-1.364 0-1.891-.806-2.295-1.798L8.917 10.117z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1fb';
-->
