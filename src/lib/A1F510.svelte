<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f510';
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
    fill="#AAB8C2"
    d="M13 3C7.477 3 3 7.477 3 13v10h4V13c0-3.313 2.687-6 6-6s6 2.687 6 6v10h4V13c0-5.523-4.477-10-10-10z"
  /><path
    fill="#FFAC33"
    d="M26 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V20c0-2.209 1.791-4 4-4h18c2.209 0 4 1.791 4 4v12z"
  /><path
    fill="#C1694F"
    d="M35 9c0-4.971-4.029-9-9-9s-9 4.029-9 9c0 3.917 2.507 7.24 6 8.477V33.5c0 1.381 1.119 2.5 2.5 2.5 1.213 0 2.223-.864 2.45-2.01.018.001.032.01.05.01.553 0 1-.447 1-1v-1c0-.553-.447-1-1-1v-1c.553 0 1-.447 1-1v-2c0-.553-.447-1-1-1v-2.277c.596-.347 1-.984 1-1.723v-4.523c3.493-1.236 6-4.559 6-8.477zm-9-7c1.104 0 2 .896 2 2s-.896 2-2 2-2-.896-2-2 .896-2 2-2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f510';
-->
