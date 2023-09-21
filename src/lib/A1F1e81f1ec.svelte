<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e8 1f1ec';
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
    fill="#009543"
    d="M4 5C1.791 5 0 6.791 0 9v18c0 1.104.448 2.104 1.172 2.828L26 5H4z"
  /><path
    fill="#FBDE4A"
    d="M32 5h-6L1.172 29.828C1.896 30.552 2.896 31 4 31h6L34.828 6.172C34.104 5.448 33.104 5 32 5z"
  /><path
    fill="#DC241F"
    d="M10 31h22c2.209 0 4-1.791 4-4V9c0-1.104-.448-2.104-1.172-2.828L10 31z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e8 1f1ec';
-->
