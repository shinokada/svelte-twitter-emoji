<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '2639';
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
    fill="#FFCC4D"
    d="M36 18c0 9.941-8.059 18-18 18-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18"
  /><ellipse fill="#664500" cx="11.5" cy="14.5" rx="2.5" ry="3.5" /><ellipse
    fill="#664500"
    cx="24.5"
    cy="14.5"
    rx="2.5"
    ry="3.5"
  /><path
    fill="#664500"
    d="M8.665 27.871c.178.161.444.171.635.029.039-.029 3.922-2.9 8.7-2.9 4.766 0 8.662 2.871 8.7 2.9.191.142.457.13.635-.029.177-.16.217-.424.094-.628C27.3 27.029 24.212 22 18 22s-9.301 5.028-9.429 5.243c-.123.205-.084.468.094.628z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '2639';
-->
