<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f48d';
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
    fill="#9AAAB4"
    d="M18 12c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm0 20c-4.418 0-8-3.582-8-8s3.582-8 8-8 8 3.582 8 8-3.582 8-8 8z"
  /><path fill="#5DADEC" d="M29 5l-4-5H11L7 5l11 9z" /><path
    fill="#8CCAF7"
    d="M29 5l-4-5H11L7 5h11z"
  /><path fill="#5DADEC" d="M29 5l-4-5h-7v5h1z" /><path fill="#8CCAF7" d="M18 5h11l-11 9z" /><path
    fill="#9AAAB4"
    d="M25 13c0 1.657-1.343 3-3 3h-8c-1.657 0-3-1.343-3-3s1.343-3 3-3h8c1.657 0 3 1.343 3 3z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f48d';
-->
