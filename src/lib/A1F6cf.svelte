<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6cf';
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
  ><path fill="#C1694F" d="M1 28h34v5H1z" /><path
    fill="#C1694F"
    d="M36 35c0 .553-.447 1-1 1-.553 0-1-.447-1-1V21c0-.553.447-1 1-1 .553 0 1 .447 1 1v14zM0 35c0 .553.447 1 1 1 .553 0 1-.447 1-1V13c0-.552-.447-1-1-1-.553 0-1 .448-1 1v22z"
  /><path fill="#269" d="M32 23H4c-1.104 0-2 .896-2 2v4h32v-4c0-1.104-.896-2-2-2z" /><path
    fill="#55ACEE"
    d="M32 23H4c-1.104 0-2 .896-2 2v4h32v-4c0-1.104-.896-2-2-2z"
  /><path
    fill="#5C913B"
    d="M2.126 19.938c-.261 1.073 1.485 2.419 3.9 3.006 2.415.587 4.584.192 4.846-.881.261-1.073-1.485-2.419-3.9-3.007-2.415-.587-4.585-.192-4.846.882z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6cf';
-->
