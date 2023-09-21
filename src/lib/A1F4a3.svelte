<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4a3';
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
  ><path fill="#CCD6DD" d="M24.187 9.657l5.658-5.654L32 6.16l-5.658 5.655z" /><circle
    fill="#31373D"
    cx="14"
    cy="22"
    r="14"
  /><path fill="#31373D" d="M19 11.342l5.658-5.657 5.657 5.658L24.657 17z" /><circle
    fill="#F18F26"
    cx="32"
    cy="4"
    r="4"
  /><circle fill="#FDCB58" cx="32" cy="4" r="2" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4a3';
-->
