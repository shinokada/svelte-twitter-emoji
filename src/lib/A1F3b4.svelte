<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3b4';
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
  ><path fill="#DD2E44" d="M32 28H4V4c0-2.209 1.791-4 4-4h20c2.209 0 4 1.791 4 4v24z" /><path
    d="M8 36h20c2.209 0 4-1.791 4-4v-4c-4.117-2.744-21.139-8.233-28 0v4c0 2.209 1.791 4 4 4z"
  /><circle fill="#FFF" cx="15.276" cy="12.495" r="7.578" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3b4';
-->
