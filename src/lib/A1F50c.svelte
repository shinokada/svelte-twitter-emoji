<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f50c';
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
    fill="#9AAAB4"
    d="M11.858 16.264c.389.389.389 1.025 0 1.414s-1.025.389-1.414 0L1.959 9.192c-.389-.389-.389-1.025 0-1.414s1.025-.389 1.414 0l8.485 8.486zm7.072-7.071c.389.389.389 1.025 0 1.414s-1.025.389-1.414 0L9.029 2.121c-.389-.389-.389-1.025 0-1.414s1.025-.389 1.414 0l8.487 8.486z"
  /><path
    fill="#31373D"
    d="M34 36c0-4.966-2.56-8.581-4.562-10.65.898-1.532.704-3.529-.61-4.844l-1.099-1.099c.352-1.332.021-2.806-1.022-3.851l-4.949-4.95c.78-.781.78-2.047 0-2.828-.781-.781-2.049-.781-2.829-.001l-2.826 2.826-.003.002-4.242 4.243-2.828 2.828c-.781.781-.781 2.047 0 2.828.781.781 2.047.781 2.828 0l4.95 4.95c1.044 1.044 2.519 1.373 3.85 1.021l1.101 1.101c1.318 1.318 3.323 1.51 4.857.602C28.099 29.726 30 32.404 30 36h4z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f50c';
-->
