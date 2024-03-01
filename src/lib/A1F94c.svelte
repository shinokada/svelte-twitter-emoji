<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f94c';
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
    fill="#BE1931"
    d="M28 12H13V8c0-.552.448-1 1-1h11c1.104 0 2-.896 2-2s-.896-2-2-2H14c-2.761 0-5 2.239-5 5v4H8c-1.104 0-2 .896-2 2s.896 2 2 2h20c1.104 0 2-.896 2-2s-.896-2-2-2z"
  /><path
    fill="#66757F"
    d="M36 25c0 3.313-2.687 6-6 6H6c-3.313 0-6-2.687-6-6v-5c0-3.313 2.687-6 6-6h24c3.313 0 6 2.687 6 6v5z"
  /><path fill="#99AAB5" d="M0 20h36v5H0z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f94c';
-->
