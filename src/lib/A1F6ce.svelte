<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6ce';
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
  ><path fill="#F4900C" d="M15 26h6v4h-6z" /><path
    fill="#FFAC33"
    d="M30 18c0 7 3 4 3 7 0 0 0 2-2 2H5c-2 0-2-2-2-2 0-3 3 0 3-7 0-5.523 6.477-8 12-8s12 2.477 12 8z"
  /><circle fill="#FFAC33" cx="18" cy="10" r="3" /><path
    fill="#C1694F"
    d="M35 33c0 1.104-.896 2-2 2H3c-1.104 0-2-.896-2-2s.896-2 2-2h30c1.104 0 2 .896 2 2z"
  /><path
    fill="#C1694F"
    d="M33 31c0 1.104-.896 2-2 2H5c-1.104 0-2-.896-2-2s.896-2 2-2h26c1.104 0 2 .896 2 2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6ce';
-->
