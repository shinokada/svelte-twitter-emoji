<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f8 1f1e8';
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
    fill="#D62828"
    d="M32 5h-7.833L1.129 29.785l.001.001c.152.157.317.301.493.431l.001.001L36 13.667V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="#FCD856"
    d="M.763 29.35c.112.154.235.299.367.435L24.167 5H12L.763 29.35c-.001-.001-.001-.001 0 0z"
  /><path fill="#003F87" d="M12 5H4C1.791 5 0 6.791 0 9v18c0 .878.283 1.689.762 2.349L12 5z" /><path
    fill="#EEE"
    d="M2.063 30.501l.004.002L36 22.333v-8.667L1.624 30.218c.14.103.287.198.439.283z"
  /><path
    fill="#007A3D"
    d="M4 31h28c2.209 0 4-1.791 4-4v-4.667L2.067 30.502C2.64 30.819 3.299 31 4 31z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f8 1f1e8';
-->
