<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4d4';
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
    fill="#C1694F"
    d="M35 26c0 2.209-1.791 4-4 4H5c-2.209 0-4-1.791-4-4V6.313C1 4.104 6.791 0 9 0h20.625C32.719 0 35 2.312 35 5.375V26z"
  /><path
    fill="#CCD6DD"
    d="M33 30c0 2.209-1.791 4-4 4H7c-2.209 0-4-1.791-4-4V6c0-4.119-.021-4 5-4h21c2.209 0 4 1.791 4 4v24z"
  /><path
    fill="#E1E8ED"
    d="M31 31c0 1.657-1.343 3-3 3H4c-1.657 0-3-1.343-3-3V7c0-1.657 1.343-3 3-3h24c1.657 0 3 1.343 3 3v24z"
  /><path
    fill="#C1694F"
    d="M31 32c0 2.209-1.791 4-4 4H6c-2.209 0-4-1.791-4-4V10c0-2.209 1.791-4 4-4h21c2.209 0 4 1.791 4 4v22z"
  /><path
    fill="#D99E82"
    d="M29 32c0 2.209-1.791 4-4 4H6c-2.209 0-4-1.791-4-4V12c0-2.209 1.791-4 4-4h19.335C27.544 8 29 9.456 29 11.665V32z"
  /><path
    fill="#C1694F"
    d="M6 6C4.312 6 4.269 4.078 5 3.25 5.832 2.309 7.125 2 9.438 2H11V0H8.281C4.312 0 1 2.5 1 5.375V32c0 2.209 1.791 4 4 4h2V6H6z"
  /><path
    fill="#E1E8ED"
    d="M25 18c0 1.104-.896 2-2 2H13c-1.104 0-2-.896-2-2v-2c0-1.104.896-2 2-2h10c1.104 0 2 .896 2 2v2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4d4';
-->
