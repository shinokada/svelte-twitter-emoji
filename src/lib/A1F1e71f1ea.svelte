<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e7 1f1ea';
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
  xml:space="preserve"
  ><path fill="#141414" d="M7 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h6V5H7z" /><path
    fill="#FDDA24"
    d="M13 5h10v26H13z"
  /><path fill="#EF3340" d="M29 5h-6v26h6a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e7 1f1ea';
-->
