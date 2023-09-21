<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f55a';
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
  ><circle fill="#99AAB5" cx="18" cy="18" r="18" /><circle
    fill="#E1E8ED"
    cx="18"
    cy="18"
    r="14"
  /><path
    fill="#67757F"
    d="M18 19c-.552 0-1-.447-1-1V6c0-.552.448-1 1-1 .553 0 1 .448 1 1v12c0 .553-.447 1-1 1z"
  /><path
    fill="#67757F"
    d="M18.001 19c-.367 0-.72-.202-.896-.553l-4-8c-.247-.494-.047-1.095.447-1.342.496-.248 1.095-.046 1.342.447l4 8c.247.494.047 1.095-.447 1.342-.143.072-.296.106-.446.106z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f55a';
-->
