<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ea 1f1fa';
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
    fill="#039"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path
    d="M18.539 9.705l.849-.617h-1.049l-.325-.998-.324.998h-1.049l.849.617-.325.998.849-.617.849.617zm0 17.333l.849-.617h-1.049l-.325-.998-.324.998h-1.049l.849.617-.325.998.849-.617.849.617zm-8.666-8.667l.849-.617h-1.05l-.324-.998-.325.998H7.974l.849.617-.324.998.849-.617.849.617zm1.107-4.285l.849-.617h-1.05l-.324-.998-.324.998h-1.05l.849.617-.324.998.849-.617.849.617zm0 8.619l.849-.617h-1.05l-.324-.998-.324.998h-1.05l.849.617-.324.998.849-.617.849.617zm3.226-11.839l.849-.617h-1.05l-.324-.998-.324.998h-1.05l.849.617-.324.998.849-.617.849.617zm0 15.067l.849-.617h-1.05l-.324-.998-.324.998h-1.05l.849.617-.324.998.849-.616.849.616zm11.921-7.562l-.849-.617h1.05l.324-.998.325.998h1.049l-.849.617.324.998-.849-.617-.849.617zm-1.107-4.285l-.849-.617h1.05l.324-.998.324.998h1.05l-.849.617.324.998-.849-.617-.849.617zm0 8.619l-.849-.617h1.05l.324-.998.324.998h1.05l-.849.617.324.998-.849-.617-.849.617zm-3.226-11.839l-.849-.617h1.05l.324-.998.324.998h1.05l-.849.617.324.998-.849-.617-.849.617zm0 15.067l-.849-.617h1.05l.324-.998.324.998h1.05l-.849.617.324.998-.849-.616-.849.616z"
    fill="#FC0"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ea 1f1fa';
-->
