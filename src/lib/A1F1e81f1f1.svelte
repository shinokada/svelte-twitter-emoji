<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e8 1f1f1';
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
    fill="#1F429B"
    d="M13 5H4C1.791 5 0 6.791 0 9v9h13V5zm-4.663 9.292l-1.882-1.367-1.882 1.367.719-2.212-1.882-1.368h2.326L6.455 8.5l.719 2.212H9.5L7.618 12.08l.719 2.212z"
  /><path fill="#EEE" d="M32 5H13v13h23V9c0-2.209-1.791-4-4-4z" /><path
    fill="#D42D27"
    d="M0 18v9c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-9H0z"
  /><path
    fill="#FFF"
    d="M7.174 10.712L6.455 8.5l-.719 2.212H3.41l1.882 1.368-.719 2.212 1.882-1.367 1.882 1.367-.719-2.212L9.5 10.712z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e8 1f1f1';
-->
