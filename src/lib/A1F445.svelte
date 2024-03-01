<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f445';
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
    fill="#662113"
    d="M36 7.5C36 12 27.941 19 18 19S0 12 0 7.5C0 6 3 9 18 9s18-3 18-1.5z"
  /><path
    fill="#EA596E"
    d="M18 11c-6 0-11-1-11-1v12c0 6.075 4.925 11 11 11s11-4.925 11-11V10s-5 1-11 1z"
  /><path
    fill="#DD2E44"
    d="M19 29c0 .553-.448 1-1 1s-1-.447-1-1V13c0-.552.448-1 1-1s1 .448 1 1v16z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f445';
-->
