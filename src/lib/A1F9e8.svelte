<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f9e8';
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
  ><circle fill="#FFE8B6" cx="29" cy="4" r="4" /><circle fill="#FFD983" cx="29" cy="4" r="3" /><path
    fill="#FFCC4D"
    d="M32.5.5l-4.207 2.793 1.414 1.414zm-7 7l2.793-4.207 1.414 1.414z"
  /><path fill="#FFCC4D" d="M32.5 7.5l-2.793-4.207-1.414 1.414z" /><path
    fill="#FFCC4D"
    d="M25.5.5l4.207 2.793-1.414 1.414z"
  /><path
    fill="#C1694F"
    d="M23 13.5c-.143 0-.285-.061-.384-.18-.177-.212-.148-.528.063-.705 5.709-4.757 5.82-8.581 5.82-8.619.003-.275.209-.534.503-.496.276.003.498.225.498.5 0 .173-.07 4.293-6.18 9.384-.093.078-.207.116-.32.116z"
  /><path
    fill="#DD2E44"
    d="M4.826 35.417L.583 31.174c-.778-.778-.778-2.051 0-2.828L19.675 9.254c.778-.778 2.051-.778 2.828 0l4.243 4.243c.778.778.778 2.051 0 2.828L7.654 35.417c-.777.777-2.05.777-2.828 0z"
  /><path
    fill="#FFCC4D"
    d="M18.261 10.668l7.071 7.07-2.121 2.122-7.071-7.071zM4.12 24.81l7.07 7.07-2.12 2.122-7.072-7.07z"
  /><path
    fill="#EA596E"
    d="M22.504 9.254l1.414 1.414-2.828 2.828-1.415-1.414zM3.412 28.346l1.414 1.414-2.828 2.828-1.414-1.414zm14.142-14.142l1.414 1.414-12.02 12.02-1.415-1.414z"
  /><path
    fill="#FFD983"
    d="M19.675 12.082l1.415 1.414-2.122 2.122-1.414-1.415zM5.534 26.224l1.414 1.415-2.122 2.12-1.414-1.413z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f9e8';
-->
