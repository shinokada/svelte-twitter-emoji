<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4fa';
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
  ><path fill="#31373D" d="M35 31s0 4-4 4H5c-4 0-4-4-4-4V12c0-4 4-4 4-4h26s4 0 4 4v19z" /><path
    fill="#31373D"
    d="M21.303 10.389c.391.391.391 1.023 0 1.414s-1.023.391-1.414 0l-9.192-9.192c-.391-.391-.391-1.023 0-1.414s1.023-.391 1.414 0l9.192 9.192z"
  /><path
    fill="#31373D"
    d="M14.697 10.389c-.391.391-.391 1.023 0 1.414s1.023.391 1.414 0l9.192-9.192c.391-.391.391-1.023 0-1.414s-1.023-.391-1.414 0l-9.192 9.192z"
  /><path
    fill="#55ACEE"
    d="M18 11c8 0 10 1 11 2s2 3 2 8-1 7-2 8-3 2-11 2-10-1-11-2-2-3-2-8 1-7 2-8 3-2 11-2z"
  /><circle fill="#66757F" cx="31.5" cy="31.5" r="1.5" /><circle
    fill="#66757F"
    cx="4.5"
    cy="31.5"
    r="1.5"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4fa';
-->
