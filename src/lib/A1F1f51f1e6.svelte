<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f5 1f1e6';
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
    fill="#EEE"
    d="M18 18V5H4C1.791 5 0 6.791 0 9v9h18zm0 0v13h14c2.209 0 4-1.791 4-4v-9H18z"
  /><path fill="#005293" d="M18 18v13H4c-2.209 0-4-1.791-4-4v-9h18z" /><path
    fill="#D21034"
    d="M18 18V5h14c2.209 0 4 1.791 4 4v9H18z"
  /><path
    fill="#005293"
    d="M9.674 10.573L9 8.5l-.674 2.073H6.147l1.763 1.281-.673 2.073L9 12.646l1.763 1.281-.673-2.073 1.763-1.281z"
  /><path
    fill="#D21034"
    d="M25.91 24.854l-.673 2.073L27 25.646l1.763 1.281-.673-2.073 1.763-1.281h-2.179L27 21.5l-.674 2.073h-2.179z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f5 1f1e6';
-->
