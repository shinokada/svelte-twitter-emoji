<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f346';
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
    fill="#744EAA"
    d="M6 4c3 0 5 2 8 6s7.957 7.191 12 8c5 1 9 5 9 11 0 4.897-3.846 7-9 7-5 0-9-3-14-8S2 14 2 10s1-6 4-6z"
  /><path
    fill="#77B255"
    d="M3.515 0c1.248 0 1.248 1.248 1.248 2.495 0 1.764 1.248 1.129 2.496 1.129C8.505 3.624 11 6 11 6H7.258c-1.248 0 0 2.614-1.248 2.614S4.762 7.426 3.515 7.426 2 11 2 11s-1.604-4.153.267-6.024C3.515 3.728 1.02 0 3.515 0z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f346';
-->
