<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1faa7';
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
    fill="#D99E82"
    d="M20 33.5v-31c0-.828-.672-1.5-1.5-1.5h-2c-.828 0-1.5.672-1.5 1.5v31c0 .828.672 1.5 1.5 1.5h2c.828 0 1.5-.672 1.5-1.5z"
  /><path
    fill="#E1E8ED"
    d="M28 21H7c-1.105 0-2-.895-2-2V5c0-1.105.895-2 2-2h21c1.105 0 2 .895 2 2v14c0 1.105-.895 2-2 2z"
  /><path
    fill="#66757F"
    d="M17 14h-7c-.552 0-1-.448-1-1s.448-1 1-1h7c.552 0 1 .448 1 1s-.448 1-1 1zm8 0h-4c-.553 0-1-.448-1-1s.447-1 1-1h4c.553 0 1 .448 1 1s-.447 1-1 1zm0-5H10c-.552 0-1-.448-1-1s.448-1 1-1h15c.553 0 1 .448 1 1s-.447 1-1 1z"
  /><path fill="#C1694F" d="M15 21h5v2h-5z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1faa7';
-->
