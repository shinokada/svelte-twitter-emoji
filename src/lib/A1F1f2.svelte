<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f2';
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
    fill="#3B88C3"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M8.174 9.125c.186-1.116 1.395-2.387 3.039-2.387 1.55 0 2.76 1.116 3.101 2.232l3.659 12.278h.062L21.692 8.97c.341-1.116 1.55-2.232 3.101-2.232 1.642 0 2.852 1.271 3.039 2.387l2.883 17.302c.031.186.031.372.031.526 0 1.365-.992 2.232-2.232 2.232-1.582 0-2.201-.713-2.418-2.17l-1.83-12.619h-.062l-3.721 12.991c-.217.744-.805 1.798-2.48 1.798-1.674 0-2.263-1.054-2.48-1.798l-3.721-12.991h-.062l-1.83 12.62c-.217 1.457-.837 2.17-2.418 2.17-1.24 0-2.232-.867-2.232-2.232 0-.154 0-.341.031-.526L8.174 9.125z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f2';
-->
