<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3f7';
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
    fill="#FFD983"
    d="M32.017 20.181L17.345 5.746C16.687 5.087 15.823 5 14.96 5H4.883C3.029 5 2 6.029 2 7.883v10.082c0 .861.089 1.723.746 2.38L17.3 35.017c1.311 1.31 3.378 1.31 4.688 0l10.059-10.088c1.31-1.312 1.28-3.438-.03-4.748zm-23.596-8.76c-.585.585-1.533.585-2.118 0s-.586-1.533 0-2.118c.585-.586 1.533-.585 2.118 0 .585.586.586 1.533 0 2.118z"
  /><path
    fill="#D99E82"
    d="M9.952 7.772c-1.43-1.431-3.749-1.431-5.179 0-1.431 1.43-1.431 3.749 0 5.18 1.43 1.43 3.749 1.43 5.18 0 1.43-1.431 1.429-3.749-.001-5.18zm-1.53 3.65c-.585.585-1.534.585-2.119 0-.585-.585-.586-1.534 0-2.119.585-.587 1.534-.585 2.119 0 .585.585.586 1.533 0 2.119z"
  /><path
    fill="#C1694F"
    d="M8.507 10.501c-.391.391-1.023.391-1.415 0-.391-.391-.39-1.023 0-1.414L15.577.602c.391-.391 1.023-.391 1.415 0 .391.391.39 1.023 0 1.414l-8.485 8.485z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3f7';
-->
