<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f685';
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
  ><path fill="#939598" d="M0 34h36v2H0z" /><path
    fill="#D1D3D4"
    d="M3 35h33V6H21c-4 0-5 2-5 2l-4 6S0 19 0 24c0 4 6 6 6 6l-3 5z"
  /><path fill="#231F20" d="M14 35l2-3h20v3z" /><path
    d="M0 23.999c0 4 6 6 6 6V17.125C3 19 0 21.499 0 23.999zM6 30v-.001V30z"
    fill="#3B88C3"
  /><path fill="#269" d="M6 30l-3 5h33v-5z" /><path fill="#3B88C3" d="M20 30l4-6h12v6z" /><path
    fill="#55ACEE"
    d="M26 8H16l-4 6h-.001 10.843c.477 0 1.108-.448 1.412-1l2.197-4c.303-.552.102-1-.451-1z"
  /><path fill="#3B88C3" d="M25.902 10l.549-1c.303-.552.102-1-.451-1H16l-1.333 2h11.235z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f685';
-->
