<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1eb 1f1f2';
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
    fill="#75B2DD"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path
    d="M18.3 7.6l-.584 1.797h-1.889l1.528 1.11-.583 1.796 1.528-1.11 1.528 1.11-.583-1.796 1.528-1.11h-1.889zm8.603 9.816v-1.889l-1.11 1.528-1.796-.583L25.107 18l-1.11 1.528 1.796-.583 1.11 1.528v-1.889L28.7 18zm-7.658 8.077l.583-1.796-1.528 1.11-1.528-1.11.583 1.796-1.528 1.11h1.889L18.3 28.4l.584-1.797h1.889zm-8.438-8.438l-1.11-1.528v1.889L7.9 18l1.797.584v1.889l1.11-1.528 1.796.583L11.493 18l1.11-1.528z"
    fill="#FFF"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1eb 1f1f2';
-->
