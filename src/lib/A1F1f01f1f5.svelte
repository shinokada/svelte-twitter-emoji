<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f0 1f1f5';
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
    fill="#024FA2"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path fill="#EEE" d="M0 9h36v1H0zm0 17h36v1H0z" /><path
    fill="#ED1C27"
    d="M0 10h36v16H0z"
  /><path
    fill="#FFF"
    d="M13.278 23.778c3.191 0 5.778-2.587 5.778-5.778s-2.587-5.778-5.778-5.778S7.5 14.809 7.5 18s2.587 5.778 5.778 5.778zm-1.257-7.508l1.257-3.868 1.257 3.868h4.067l-3.29 2.39 1.257 3.868-3.29-2.39-3.29 2.39 1.257-3.868-3.29-2.39h4.065z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f0 1f1f5';
-->
