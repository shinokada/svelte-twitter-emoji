<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ec 1f1ed';
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
  ><path fill="#CC212D" d="M32 5H4C1.791 5 0 6.791 0 9v5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#FBD116"
    d="M15.423 22h5.185l-2.592-1.884zm3.587-4.941h3.215l-2.601 1.889.991 3.052H36v-8H18.016zm-2.602 1.889l-2.601-1.889h3.215L18.016 14H0v8h15.416z"
  /><path
    fill="#288541"
    d="M20.617 22.006L20.608 22h-5.186l-.009.006.003-.006H0v5c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-5H20.615l.002.006z"
  /><path
    d="M13.807 17.059l2.601 1.889L15.416 22l-.002.006.009-.006 2.593-1.884L20.608 22l.009.006-.002-.006-.991-3.052 2.601-1.889H19.01L18.016 14l-.994 3.059z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ec 1f1ed';
-->
