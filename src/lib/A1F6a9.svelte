<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6a9';
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
  ><path fill="#66757F" d="M13 34s0 2-2 2-2-2-2-2V2s0-2 2-2 2 2 2 2v32z" /><path
    fill="#DD2E44"
    d="M11 4c0-2.2 1.636-3.25 3.636-2.333l16.727 7.667c2 .917 2 2.417 0 3.333l-16.727 7.667C12.636 21.25 11 20.2 11 18V4z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6a9';
-->
