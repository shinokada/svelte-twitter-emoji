<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f7 1f1ea';
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
    fill="#36F"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="red"
    d="M18 18L1.368 30.012l.001.001C2.072 30.628 2.993 31 4 31h28c1.008 0 1.929-.373 2.632-.988L18 18z"
  /><path
    fill="#FF0"
    d="M18 18.019l18 1.487v-2.975zM0 16.531v2.975l18-1.487zm2.405-11.2C1.531 5.711.82 6.394.404 7.247L18 18 2.406 5.33l-.001.001zm33.191 1.916c-.417-.853-1.129-1.536-2.003-1.917L18 18 35.596 7.247zM19.5 5h-3L18 18z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f7 1f1ea';
-->
