<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f441';
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
    fill="#E1E8ED"
    d="M35.059 18c0 3.304-7.642 11-17.067 11C8.566 29 .925 22.249.925 18c0-3.314 34.134-3.314 34.134 0z"
  /><path
    fill="#292F33"
    d="M35.059 18H.925c0-3.313 7.642-11 17.067-11s17.067 7.686 17.067 11z"
  /><path
    fill="#F5F8FA"
    d="M33.817 18c0 2.904-7.087 9.667-15.826 9.667-8.74 0-15.825-5.935-15.825-9.667 0-2.912 7.085-9.666 15.825-9.666C26.73 8.333 33.817 15.088 33.817 18z"
  /><circle fill="#8B5E3C" cx="18" cy="18" r="8.458" /><circle
    fill="#292F33"
    cx="18"
    cy="18"
    r="4.708"
  /><circle fill="#F5F8FA" cx="14.983" cy="15" r="2" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f441';
-->
