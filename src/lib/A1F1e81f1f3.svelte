<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e8 1f1f3';
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
    fill="#DE2910"
    d="M36 27c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V9c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v18z"
  /><path
    fill="#FFDE02"
    d="M11.136 8.977l.736.356.589-.566-.111.81.72.386-.804.144-.144.804-.386-.72-.81.111.566-.589zm4.665 2.941l-.356.735.566.59-.809-.112-.386.721-.144-.805-.805-.144.721-.386-.112-.809.59.566zm-.957 3.779l.268.772.817.017-.651.493.237.783-.671-.467-.671.467.236-.783-.651-.493.817-.017zm-3.708 3.28l.736.356.589-.566-.111.81.72.386-.804.144-.144.804-.386-.72-.81.111.566-.589zM7 10.951l.929 2.671 2.826.058-2.253 1.708.819 2.706L7 16.479l-2.321 1.615.819-2.706-2.253-1.708 2.826-.058z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e8 1f1f3';
-->
