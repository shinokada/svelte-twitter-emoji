<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f68f';
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
  ><path fill="#6D6E71" d="M14 7h2v29h-2z" /><path
    fill="#6D6E71"
    d="M15 19h3v2h-3zm0-6h3v2h-3z"
  /><path
    fill="#BCBEC0"
    d="M29 24c0 .553-.447 1-1 1h-9c-.553 0-1-.447-1-1V10c0-.552.447-1 1-1h9c.553 0 1 .448 1 1v14z"
  /><path fill="#BE1931" d="M29 13v-3c0-.552-.447-1-1-1h-9c-.553 0-1 .448-1 1v3h11z" /><path
    fill="#6D6E71"
    d="M21 34H9l-1 1v1h14v-1zm-2-2h-8l-1 1v1h10v-1z"
  /><circle fill="#BE1931" cx="15" cy="4" r="4" /><path fill="#808285" d="M20 13h3v3h-3z" /><path
    fill="#F4900C"
    d="M20 17h3v3h-3zm0 4h3v3h-3z"
  /><path fill="#808285" d="M24 13h3v3h-3zm0 4h3v3h-3z" /><path
    fill="#F4900C"
    d="M24 21h3v3h-3z"
  /><path fill="#DD2E44" d="M13 2h4v4h-4zm7 8h7v2h-7z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f68f';
-->
