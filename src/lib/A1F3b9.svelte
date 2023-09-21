<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3b9';
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
  ><path fill="#31373D" d="M2 36s-2 0-2-2V2s0-2 2-2h32.031C36 0 36 2 36 2v32s0 2-2 2H2z" /><path
    d="M19 33s0 1 1 1h5c1 0 1-1 1-1V5h-7v28zm9-28v28s0 1 1 1h4c1 0 1-1 1-1V5h-6zM10 33s0 1 1 1h5c1 0 1-1 1-1V5h-7v28zm-8 0s0 1 1 1h4c1 0 1-1 1-1V5H2v28z"
    fill="#E1E8ED"
  /><path
    fill="#31373D"
    d="M30 23s0 1-1 1h-4c-1 0-1-1-1-1V3h6v20zm-9 0s0 1-1 1h-4c-1 0-1-1-1-1V3h6v20zm-9 0s0 1-1 1H7c-1 0-1-1-1-1V3h6v20z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3b9';
-->
