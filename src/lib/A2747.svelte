<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '2747';
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
    fill="#77B255"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><circle fill="#FFF" cx="18" cy="18" r="3" /><path
    fill="#FFF"
    d="M20 4c0-1.104-.896-2-2-2s-2 .896-2 2v8c0 1.104.896 2 2 2s2-.896 2-2V4zm0 20c0-1.104-.896-2-2-2s-2 .896-2 2v8c0 1.104.896 2 2 2s2-.896 2-2v-8zM4 16c-1.104 0-2 .896-2 2s.896 2 2 2h8c1.104 0 2-.896 2-2s-.896-2-2-2H4zm20 0c-1.104 0-2 .896-2 2s.896 2 2 2h8c1.104 0 2-.896 2-2s-.896-2-2-2h-8zm-8.829-2.243c.391.391.391 1.024 0 1.414-.39.391-1.024.391-1.414 0L6.272 7.687c-.391-.391-.391-1.024 0-1.415s1.024-.391 1.415 0l7.484 7.485zm14.557 14.556c.392.391.391 1.024 0 1.414-.39.391-1.023.392-1.414 0l-7.485-7.485c-.391-.391-.391-1.023 0-1.414s1.024-.391 1.414 0l7.485 7.485zm-15.971-7.485c.391-.391 1.024-.391 1.414 0 .391.391.391 1.024 0 1.414l-7.485 7.486c-.391.391-1.024.391-1.415 0s-.391-1.024 0-1.415l7.486-7.485zM28.313 6.272c.391-.392 1.024-.391 1.414 0 .391.39.392 1.023 0 1.414l-7.485 7.485c-.391.391-1.023.391-1.414 0s-.391-1.023 0-1.414l7.485-7.485z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '2747';
-->
