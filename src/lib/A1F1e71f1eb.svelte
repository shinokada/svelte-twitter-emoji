<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e7 1f1eb';
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
    fill="#009E49"
    d="M19.602 18.942l.99 3.048L18 20.106l-2.593 1.884.99-3.048L15.101 18H0v9c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-9H20.899l-1.297.942z"
  /><path
    fill="#EF2B2D"
    d="M32 5H4C1.791 5 0 6.791 0 9v9h15.101l-1.296-.942h3.205L18 14.01l.99 3.048h3.205L20.899 18H36V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="#FCD116"
    d="M15.407 21.99L18 20.106l2.593 1.884-.991-3.048L20.899 18l1.296-.942H18.99L18 14.01l-.99 3.048h-3.205l1.296.942 1.297.942z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e7 1f1eb';
-->
