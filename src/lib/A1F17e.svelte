<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f17e';
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
    fill="#DD2E44"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M6.993 18.001c0-6.656 4.48-11.776 11.007-11.776 6.432 0 11.008 5.28 11.008 11.776 0 6.623-4.449 11.774-11.008 11.774-6.496 0-11.007-5.151-11.007-11.774zm17.023 0c0-3.872-2.016-7.36-6.016-7.36s-6.015 3.488-6.015 7.36c0 3.903 1.952 7.359 6.015 7.359 4.065 0 6.016-3.456 6.016-7.359z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f17e';
-->
