<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f6 1f1e6';
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
  ><path fill="#8D1B3D" d="M32 5H11v26h21c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z" /><path
    fill="#EEE"
    d="M11 28.111l5.295-1.444L11 25.222l5.295-1.444L11 22.333l5.295-1.444L11 19.444 16.295 18 11 16.556l5.295-1.444L11 13.667l5.295-1.444L11 10.778l5.295-1.445L11 7.889l5.295-1.444L11 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h7l5.295-1.444L11 28.111z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f6 1f1e6';
-->
