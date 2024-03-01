<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f0 1f1f3';
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
  ><path fill="#009E49" d="M4 5C1.791 5 0 6.791 0 9v15.323L26.496 5H4z" /><path
    fill="#CE1126"
    d="M32 31c2.209 0 4-1.791 4-4V11.186L8.767 31H32z"
  /><path
    fill="#FCD116"
    d="M26.496 5L0 24.323v1.874L29.066 5zM8.767 31L36 11.186V9.312L6.197 31z"
  /><path
    fill="#141414"
    d="M32 5h-2.934L0 26.197V27c0 2.209 1.791 4 4 4h2.197L36 9.312V9c0-2.209-1.791-4-4-4z"
  /><path
    d="M27.152 9.729l-2.074 1.513-2.079-1.505.798 2.439-2.074 1.513 2.567-.005.797 2.44.789-2.443 2.567-.004-2.08-1.505zM13.185 19.915l-2.074 1.513-2.079-1.505.798 2.439-2.074 1.513 2.567-.005.797 2.44.789-2.443 2.567-.004-2.08-1.505z"
    fill="#FFF"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f0 1f1f3';
-->
