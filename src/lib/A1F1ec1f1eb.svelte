<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ec 1f1eb';
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
    fill="#078930"
    d="M32 5H4c-1.006 0-1.915.384-2.618.998L16.228 16.72h.828L18 13.814l.944 2.906H22l-2.472 1.796.249.767 14.841 10.718C35.458 29.269 36 28.203 36 27V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="#FCDD09"
    d="M20.472 21.422L18 19.626l-2.472 1.796.944-2.906L14 16.72h2.228L1.382 5.998C.542 6.731 0 7.797 0 9v18c0 2.209 1.791 4 4 4h28c1.006 0 1.915-.384 2.618-.998L19.777 19.284l.695 2.138z"
  /><path
    fill="#DA121A"
    d="M16.472 18.516l-.944 2.906L18 19.626l2.472 1.796-.695-2.138-.249-.768L22 16.72h-3.056L18 13.814l-.944 2.906H14z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ec 1f1eb';
-->
