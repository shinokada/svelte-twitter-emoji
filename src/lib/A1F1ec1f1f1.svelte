<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ec 1f1f1';
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
  ><path fill="#D00C33" d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-9H0v9z" /><path
    fill="#EEE"
    d="M32 5H4C1.791 5 0 6.791 0 9v9h36V9c0-2.209-1.791-4-4-4z"
  /><circle fill="#EEE" cx="13.5" cy="18" r="8" /><path
    fill="#D00C33"
    d="M13.5 10c-4.418 0-8 3.582-8 8h16c0-4.418-3.582-8-8-8z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ec 1f1f1';
-->
