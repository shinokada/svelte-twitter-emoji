<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f505';
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
    fill="#FFAC33"
    d="M18 8C12.477 8 8 12.477 8 18s4.477 10 10 10 10-4.477 10-10S23.523 8 18 8zm0 16c-3.314 0-6-2.685-6-6 0-3.313 2.686-6 6-6s6 2.687 6 6c0 3.315-2.687 6-6 6z"
  /><circle fill="#FFAC33" cx="18" cy="5" r="2" /><circle
    fill="#FFAC33"
    cx="18"
    cy="31"
    r="2"
  /><path
    fill="#FFAC33"
    d="M10.222 7.394c-.781-.781-2.047-.781-2.828 0-.781.781-.781 2.047 0 2.829.781.781 2.047.781 2.828 0 .781-.782.781-2.048 0-2.829zm18.384 18.384c.781.78.781 2.048 0 2.828-.781.781-2.047.78-2.828 0-.781-.781-.781-2.047 0-2.828.782-.78 2.047-.781 2.828 0z"
  /><circle fill="#FFAC33" cx="5" cy="18" r="2" /><circle
    fill="#FFAC33"
    cx="31"
    cy="18"
    r="2"
  /><path
    fill="#FFAC33"
    d="M28.605 10.222c.781-.781.781-2.047.001-2.828-.781-.781-2.048-.781-2.829 0-.78.781-.781 2.047 0 2.828.782.781 2.048.781 2.828 0zM10.222 28.606c-.781.781-2.047.781-2.828 0-.781-.781-.781-2.047 0-2.828.781-.781 2.047-.781 2.828 0 .78.782.781 2.047 0 2.828z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f505';
-->
