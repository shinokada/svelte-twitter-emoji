<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e7 1f1f8';
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
    fill="#00ABC9"
    d="M1.364 29.987C2.069 30.61 2.985 31 4 31h28c2.209 0 4-1.791 4-4v-4.5H11.442L1.364 29.987z"
  /><path fill="#FAE042" d="M17.5 18l-6.058 4.5H36v-9H11.442z" /><path
    fill="#00ABC9"
    d="M32 5H4c-1.015 0-1.931.39-2.636 1.013L11.442 13.5H36V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="#141414"
    d="M17.5 18l-6.058-4.5L1.364 6.013C.534 6.746 0 7.806 0 9v18c0 1.194.534 2.254 1.364 2.987L11.442 22.5 17.5 18z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e7 1f1f8';
-->
