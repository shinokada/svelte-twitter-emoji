<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3f3';
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
    fill="#8899A6"
    d="M5 36c-1.104 0-2-.896-2-2V3c0-1.104.896-2 2-2s2 .896 2 2v31c0 1.104-.896 2-2 2z"
  /><path
    fill="#AAB8C2"
    d="M5 1c-1.105 0-2 .895-2 2v31c0 .276.224.5.5.5s.5-.224.5-.5V4.414C4 3.633 4.633 3 5.414 3H7c0-1.105-.895-2-2-2z"
  /><path
    fill="#8899A6"
    d="M5 36c-1.104 0-2-.896-2-2V3c0-1.104.896-2 2-2s2 .896 2 2v31c0 1.104-.896 2-2 2z"
  /><path
    fill="#AAB8C2"
    d="M5 1c-1.105 0-2 .895-2 2v31c0 .276.224.5.5.5s.5-.224.5-.5V4.414C4 3.633 4.633 3 5.414 3H7c0-1.105-.895-2-2-2z"
  /><path
    fill="#E1E8ED"
    d="M32.415 3.09c-1.752-.799-3.615-1.187-5.698-1.187-2.518 0-5.02.57-7.438 1.122-2.418.551-4.702 1.072-6.995 1.072-1.79 0-3.382-.329-4.868-1.006-.309-.142-.67-.115-.956.068C6.173 3.343 6 3.66 6 4v19c0 .392.229.747.585.91 1.752.799 3.616 1.187 5.698 1.187 2.518 0 5.02-.57 7.438-1.122 2.418-.551 4.702-1.071 6.995-1.071 1.79 0 3.383.329 4.868 1.007.311.14.67.115.956-.069.287-.185.46-.502.46-.842V4c0-.392-.229-.748-.585-.91z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3f3';
-->
