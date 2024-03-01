<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e6 1f1fc';
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
    fill="#4189DD"
    d="M32 5H4C1.791 5 0 6.791 0 9v13.055h36V9c0-2.209-1.791-4-4-4zM6.276 11.276l-.943 3.057-.943-3.057-3.057-.943L4.39 9.39l.943-3.057.943 3.057 3.057.943-3.057.943zM4 31h28c1.872 0 3.431-1.291 3.867-3.028H.133C.569 29.709 2.128 31 4 31zm-4-6.972h36V26H0z"
  /><path
    fill="#FFF"
    d="M5.333 6.333l-.942 3.058-3.057.943 3.057.943.943 3.057.943-3.057 3.057-.943-3.058-.943-.943-3.058zm.727 4.727l-.726 2.355-.727-2.355-2.355-.726 2.355-.726.726-2.355.727 2.354 2.355.726-2.355.727z"
  /><path
    fill="#D21034"
    d="M5.333 7.252l-.726 2.355-2.355.726 2.355.727.726 2.355.727-2.355 2.355-.727-2.355-.726z"
  /><path
    fill="#F9D616"
    d="M0 22.055h36v1.972H0zM0 27c0 .337.054.659.133.972h35.734c.079-.313.133-.635.133-.972v-1H0v1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e6 1f1fc';
-->
