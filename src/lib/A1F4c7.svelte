<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4c7';
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
    fill="#292F33"
    d="M32 13H4c-2.209 0-4 1.791-4 4v2c0 2.209 1.791 4 4 4v9c0 2.209 1.791 4 4 4h20c2.209 0 4-1.791 4-4v-9c2.209 0 4-1.791 4-4v-2c0-2.209-1.791-4-4-4z"
  /><path
    fill="#CCD6DD"
    d="M30 15c0 1.104-.896 2-2 2H8c-1.104 0-2-.896-2-2V2c0-1.105.896-2 2-2h20c1.104 0 2 .896 2 2v13z"
  /><path
    fill="#55ACEE"
    d="M18 13c0 .552-.447 1-1 1H9c-.552 0-1-.448-1-1V3c0-.552.448-1 1-1h8c.553 0 1 .448 1 1v10z"
  /><path
    fill="#CCD6DD"
    d="M30 32c0 1.104-.896 2-2 2H8c-1.104 0-2-.896-2-2V21c0-1.104.896-2 2-2h20c1.104 0 2 .896 2 2v11z"
  /><path
    fill="#66757F"
    d="M28 4c0 .552-.447 1-1 1h-6c-.553 0-1-.448-1-1s.447-1 1-1h6c.553 0 1 .448 1 1zm0 4c0 .552-.447 1-1 1h-6c-.553 0-1-.448-1-1s.447-1 1-1h6c.553 0 1 .448 1 1zm0 4c0 .552-.447 1-1 1h-6c-.553 0-1-.448-1-1s.447-1 1-1h6c.553 0 1 .448 1 1z"
  /><path
    fill="#99AAB5"
    d="M14 20c0 .553-.448 1-1 1s-1-.447-1-1v-4c0-.553.448-1 1-1s1 .447 1 1v4zm10 0c0 .553-.447 1-1 1-.553 0-1-.447-1-1v-4c0-.553.447-1 1-1 .553 0 1 .447 1 1v4z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4c7';
-->
