<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f9 1f1ed';
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
  ><path fill="#A7122D" d="M0 26.518V27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-.482H0z" /><path
    fill="#EEE"
    d="M0 22.181h36v4.485H0z"
  /><path fill="#292648" d="M0 13.513h36v8.821H0z" /><path
    fill="#EEE"
    d="M0 9.181h36v4.485H0z"
  /><path fill="#A7122D" d="M0 9.333V9c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v.333H0z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f9 1f1ed';
-->
