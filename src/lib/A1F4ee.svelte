<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4ee';
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
  ><path fill="#66757F" d="M14 28h9v8h-9z" /><path
    fill="#DD2E44"
    d="M31 25c0 2.209-1.791 4-4 4H9c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h18c2.209 0 4 1.791 4 4v21z"
  /><path fill="#A0041E" d="M7 8V6s0-2 2-2h18s2 0 2 2v2H7z" /><path
    fill="#292F33"
    d="M27 12H9s-2 0-2-2V7h22v3c0 2-2 2-2 2z"
  /><path fill="#E1E8ED" d="M11 7v14s0 2 2 2h10s2 0 2-2V7H11z" /><path
    fill="#CCD6DD"
    d="M13 23h9.22c-1.847-2.365-6.425-8.205-7.22-9-1-1 0-2 0-2l5-5h-9v14s0 2 2 2z"
  /><path
    fill="#66757F"
    d="M15 14c.795.795 5.373 6.635 7.22 9H23s.404-.01.848-.19L16 13l6-6h-2l-5 5s-1 1 0 2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4ee';
-->
