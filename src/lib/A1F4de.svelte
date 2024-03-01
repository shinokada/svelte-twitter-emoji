<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4de';
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
    fill="#31373D"
    d="M34.06 26.407l-3.496-3.496c-1.93-1.93-5.06-1.93-6.989 0-.719.718-1.167 1.603-1.351 2.528-5.765-1.078-11.372-6.662-11.721-11.653.947-.176 1.854-.627 2.586-1.36 1.93-1.93 1.93-5.06 0-6.99L9.594 1.94c-1.93-1.93-5.06-1.93-6.99 0-10.486 10.486 20.97 41.942 31.456 31.456 1.929-1.929 1.929-5.059 0-6.989z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4de';
-->
