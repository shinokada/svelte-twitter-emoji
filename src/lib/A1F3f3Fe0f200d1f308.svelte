<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3f3 fe0f 200d 1f308';
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
  xml:space="preserve"
  ><path fill="#880082" d="M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-.5H0v.5z" /><path
    fill="#3558A0"
    d="M0 22.07h36v4.6H0z"
  /><path fill="#138F3E" d="M0 17.83h36v4.5H0z" /><path fill="#FAD220" d="M0 13.5h36V18H0z" /><path
    fill="#FF7300"
    d="M0 9.17h36v4.5H0z"
  /><path fill="#FF000E" d="M32 5H4a4 4 0 0 0-4 4v.33h36V9a4 4 0 0 0-4-4z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3f3 fe0f 200d 1f308';
-->
