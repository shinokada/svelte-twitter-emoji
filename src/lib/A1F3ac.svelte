<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3ac';
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
    fill="#3F7123"
    d="M35.845 32c0 2.2-1.8 4-4 4h-26c-2.2 0-4-1.8-4-4V19c0-2.2 1.8-4 4-4h26c2.2 0 4 1.8 4 4v13z"
  /><path fill="#3F7123" d="M1.845 15h34v6h-34z" /><path
    fill="#CCD6DD"
    d="M1.845 15h34v7h-34z"
  /><path fill="#292F33" d="M1.845 15h4l-4 7v-7zm11 0l-4 7h7l4-7h-7zm14 0l-4 7h7l4-7h-7z" /><path
    fill="#CCD6DD"
    d="M.155 8.207L33.148 0l1.69 6.792L1.845 15z"
  /><path
    fill="#292F33"
    d="M.155 8.207l5.572 5.827L1.845 15 .155 8.207zm19.158 2.448l-5.572-5.828-6.793 1.69 5.572 5.828 6.793-1.69zm13.586-3.38l-5.572-5.828-6.793 1.69 5.572 5.827 6.793-1.689z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3ac';
-->
