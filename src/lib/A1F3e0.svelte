<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3e0';
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
    fill="#A0041E"
    d="M9.344 14.702h-2c-.276 0-.5-.224-.5-.5v-7c0-.276.224-.5.5-.5h2c.276 0 .5.224.5.5v7c0 .276-.224.5-.5.5z"
  /><path fill="#FFE8B6" d="M5 16L18 3l13 13v17H5z" /><path
    fill="#FFCC4D"
    d="M18 16h1v16h-1z"
  /><path
    fill="#66757F"
    d="M31 17c-.256 0-.512-.098-.707-.293L18 4.414 5.707 16.707c-.391.391-1.023.391-1.414 0s-.391-1.023 0-1.414l13-13c.391-.391 1.023-.391 1.414 0l13 13c.391.391.391 1.023 0 1.414-.195.195-.451.293-.707.293z"
  /><path
    fill="#66757F"
    d="M18 17c-.256 0-.512-.098-.707-.293-.391-.391-.391-1.023 0-1.414l6.5-6.5c.391-.391 1.023-.391 1.414 0s.391 1.023 0 1.414l-6.5 6.5c-.195.195-.451.293-.707.293z"
  /><path fill="#C1694F" d="M10 26h4v6h-4z" /><path
    fill="#55ACEE"
    d="M10 17h4v4h-4zm12.5 0h4v4h-4zm0 9h4v4h-4z"
  /><path
    fill="#5C913B"
    d="M33.5 33.5c0 .828-.672 1.5-1.5 1.5H4c-.828 0-1.5-.672-1.5-1.5S3.172 32 4 32h28c.828 0 1.5.672 1.5 1.5z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3e0';
-->
