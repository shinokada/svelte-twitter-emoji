<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e6 1f1ea';
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
  ><path fill="#068241" d="M32 5H9v9h27V9c0-2.209-1.791-4-4-4z" /><path
    fill="#EEE"
    d="M9 14h27v8H9z"
  /><path fill="#141414" d="M9 31h23c2.209 0 4-1.791 4-4v-5H9v9z" /><path
    fill="#EC2028"
    d="M4 5C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h5V5H4z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e6 1f1ea';
-->
