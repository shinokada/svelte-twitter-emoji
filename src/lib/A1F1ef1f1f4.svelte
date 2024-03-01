<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ef 1f1f4';
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
  ><path fill="#141414" d="M32 5H4C1.791 5 0 6.791 0 9v4.5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#007A3D"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-4.5H0V27z"
  /><path fill="#EEE" d="M0 13.5h36v9H0z" /><path
    fill="#CE1126"
    d="M1.351 6.004H1.35C.522 6.737 0 7.808 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18 1.351 6.004z"
  /><path
    fill="#FFF"
    d="M6.627 19.338l1.056.976-.105-1.435L9 18.662l-1.187-.812.717-1.247-1.375.421-.528-1.338-.528 1.338-1.375-.421.716 1.247-1.186.812 1.421.217-.104 1.435z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ef 1f1f4';
-->
