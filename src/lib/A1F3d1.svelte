<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3d1';
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
    fill="#C1694F"
    d="M4 21c2.409 0 2 2 2 3s0 3 2 3 3.464-2.465 7-6L36 0v7S22.5 21.5 18 26s-7 7-10 7c-3.513 0-7-2.605-7-7 0-4 2-5 3-5z"
  /><circle fill="#DD2E44" cx="26.5" cy="29.5" r="6.5" /><path
    fill="#FFAC33"
    d="M25.01 18.712C30.254 13.171 36 7 36 7V0L25.01 10.99v7.722zM22 21.878l1-1.049V13l-1 1v7.878z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3d1';
-->
