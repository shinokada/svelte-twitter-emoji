<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4d6';
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
    fill="#269"
    d="M32 7H4c-2.209 0-4 1.791-4 4v15c0 2.209 1.791 4 4 4h11.416c.52.596 1.477 1 2.584 1s2.065-.404 2.584-1H32c2.209 0 4-1.791 4-4V11c0-2.209-1.791-4-4-4z"
  /><path
    fill="#292F33"
    d="M20 27c0 1.104-.896 2-2 2s-2-.896-2-2V9c0-1.104.896-2 2-2s2 .896 2 2v18z"
  /><path
    fill="#99AAB5"
    d="M18 26c0 1.104-.896 2-2 2H4c-1.104 0-2-.896-2-2V8c0-1.104.896-2 2-2h12c1.104 0 2 .896 2 2v18z"
  /><path
    fill="#E1E8ED"
    d="M18 26c-.999-1.998-3.657-2-4-2-2 0-5 2-8 2-1 0-2-.896-2-2V8c0-1.104 1-2 2-2 3.255 0 6-2 8-2 3 0 4 1.896 4 3v19z"
  /><path
    fill="#99AAB5"
    d="M34 26c0 1.104-.896 2-2 2H20c-1.104 0-2-.896-2-2V8c0-1.104.896-2 2-2h12c1.104 0 2 .896 2 2v18z"
  /><path
    fill="#CCD6DD"
    d="M18 26c.999-1.998 3.657-2 4-2 2 0 5 2 8 2 1 0 2-.896 2-2V8c0-1.104-1-2-2-2-3.256 0-6-2-8-2-3 0-4 1.896-4 3v19z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4d6';
-->
