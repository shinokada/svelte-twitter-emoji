<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f2 1f1f7';
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
    fill="#CE2540"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path fill="#0F6433" d="M0 9v18h36V9z" /><path
    fill="#FFC514"
    d="M14.936 12.664l1.894 1.375-.722 2.221-.002.005.007-.005L18 14.889l1.887 1.371.006.005-.001-.005-.722-2.221 1.894-1.375h-2.341L18 10.437l-.723 2.227z"
  /><path
    fill="#FFC514"
    d="M26.1 13.641c-.019 4.458-3.638 8.067-8.1 8.067s-8.081-3.609-8.1-8.067c-.186.694-.294 1.42-.294 2.173 0 4.636 3.758 8.395 8.395 8.395s8.395-3.758 8.395-8.395c-.001-.753-.11-1.479-.296-2.173z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f2 1f1f7';
-->
