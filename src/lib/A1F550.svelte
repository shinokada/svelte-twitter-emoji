<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f550';
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
  ><circle fill="#99AAB5" cx="18" cy="18" r="18" /><circle
    fill="#E1E8ED"
    cx="18"
    cy="18"
    r="14"
  /><path
    fill="#66757F"
    d="M19 18c0 .553-.447 1-1 1-.552 0-1-.447-1-1V7c0-.552.448-1 1-1 .553 0 1 .448 1 1v11z"
  /><path
    fill="#66757F"
    d="M23.25 9.237c.479.276.643.888.367 1.366l-4.5 7.795c-.276.478-.889.642-1.367.365-.478-.276-.642-.888-.365-1.365l4.5-7.795c.276-.478.887-.642 1.365-.366z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f550';
-->
