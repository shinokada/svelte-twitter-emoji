<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f94f';
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
    fill="#F4900C"
    d="M35 21.526C35 26.758 27.389 31 18 31S1 26.758 1 21.526 7.625 11 18 11s17 5.294 17 10.526z"
  /><ellipse fill="#FFAC33" cx="18" cy="19.502" rx="16" ry="8.5" /><path
    fill="#FFD983"
    d="M18 11.331c-6.449 0-11.5 2.491-11.5 5.672 0 3.18 5.051 5.671 11.5 5.671 6.448 0 11.5-2.491 11.5-5.671 0-3.181-5.052-5.672-11.5-5.672z"
  /><ellipse fill="#FFAC33" cx="18" cy="18.002" rx="12" ry="6" /><path
    fill="#F4900C"
    d="M29 18.002c-1.81 3.118-7 4-11 4s-9.19-.882-11-4c-.75-1.292-1.5 1.083.5 3.083S14 24.402 18 24.402s8.5-1.317 10.5-3.317 1.25-4.374.5-3.083z"
  /><path
    fill="#E1E8ED"
    d="M35 1S24.497-.538 15.958 3C6.77 6.807 4 13 4 13c1.541-1.541 5.463-3.079 10.383-3.705 1.777-3.182 6.97-7.391 12.271-7.351 0 0-7.222 1.493-9.759 7.121C17.586 9.026 18.286 9 19 9c1.319 0 2.551.118 3.702.303.68-2.914 3.791-6.264 7.226-6.829 0 0-3.562 1.707-4.845 7.338C29.418 10.981 32 13 32 13c-4-8 3-12 3-12z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f94f';
-->
