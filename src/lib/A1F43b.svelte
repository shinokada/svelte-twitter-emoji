<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f43b';
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
  ><circle fill="#C1694F" cx="7" cy="6" r="6" /><circle
    fill="#C1694F"
    cx="29"
    cy="6"
    r="6"
  /><circle fill="#E6AAAA" cx="7" cy="6" r="4" /><circle fill="#E6AAAA" cx="29" cy="6" r="4" /><path
    fill="#C1694F"
    d="M35 22S33.692 0 18 0 1 22 1 22c0 5.872 4.499 10.323 12.216 11.61C14.311 35.06 16.044 36 18 36s3.688-.94 4.784-2.39C30.501 32.323 35 27.872 35 22z"
  /><circle fill="#DD2E44" cx="18" cy="30" r="4" /><path
    fill="#D99E82"
    d="M18 20S7 23.687 7 27s2.687 6 6 6c2.088 0 3.925-1.067 5-2.685C19.074 31.933 20.912 33 23 33c3.313 0 6-2.687 6-6s-11-7-11-7z"
  /><path
    fill="#272B2B"
    d="M11 17s0-2 2-2 2 2 2 2v2s0 2-2 2-2-2-2-2v-2zm10 0s0-2 2-2 2 2 2 2v2s0 2-2 2-2-2-2-2v-2zm-7.875 8c-1.624 1 3.25 4 4.875 4s6.499-3 4.874-4-8.124-1-9.749 0z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f43b';
-->
