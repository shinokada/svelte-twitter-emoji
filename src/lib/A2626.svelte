<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '2626';
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
    fill="#9266CC"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M23 6h-3V4c0-.552-.447-1-1-1h-2c-.552 0-1 .448-1 1v2h-3c-.552 0-1 .448-1 1v2c0 .552.448 1 1 1h3v22c0 .553.448 1 1 1h2c.553 0 1-.447 1-1V10h3c.553 0 1-.448 1-1V7c0-.552-.447-1-1-1z"
  /><path
    fill="#FFF"
    d="M29 13H7c-.552 0-1 .448-1 1v2c0 .553.448 1 1 1h22c.553 0 1-.447 1-1v-2c0-.552-.447-1-1-1zm-4.676 11.924l-11.429-3.657c-.526-.168-1.089.122-1.257.648l-.61 1.905c-.168.526.122 1.089.648 1.257l11.429 3.657c.526.168 1.089-.121 1.257-.648l.61-1.905c.168-.526-.121-1.089-.648-1.257z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '2626';
-->
