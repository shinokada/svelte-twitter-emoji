<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ef 1f1f2';
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
    fill="#009B3A"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="#141414"
    d="M35.762 28.361c.154-.425.238-.883.238-1.361V9c0-.477-.084-.935-.237-1.359l-.001-.002L21.416 18l14.346 10.361zM14.584 18L.238 7.639v.001C.084 8.065 0 8.523 0 9v18c0 .478.084.936.238 1.361L14.584 18z"
  /><path
    fill="#FFD202"
    d="M32.535 5.035L18 15.533 3.465 5.035h-.001C1.969 5.235.736 6.261.237 7.638L14.584 18 .238 28.361l.001.003c.499 1.375 1.731 2.4 3.223 2.6h.004L18 20.467l14.534 10.497c1.494-.2 2.728-1.224 3.227-2.601l.001-.003L21.416 18 35.762 7.639c-.498-1.378-1.732-2.404-3.227-2.604z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ef 1f1f2';
-->
