<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f9 1f1ec';
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
    fill="#006A4E"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-1.2H0V27zm15.526-6.5H15.5l20.5.1v-5.2H15.526zM32 5H15.526v5.2H36V9c0-2.209-1.791-4-4-4z"
  /><path
    fill="#FFCE00"
    d="M15.526 15.333v.067H36v-5.2H15.526zM.026 20.5L0 25.8h36v-5.2l-20.5-.1z"
  /><path fill="#D21034" d="M4 5C1.879 5 .161 6.656.026 8.743V20.5h15.5V5H4z" /><path
    fill="#FFF"
    d="M12.339 11.413H8.885l-.013-.04L7.776 8l-.022.068-1.087 3.345H3.078l2.858 2.077.045.033-1.067 3.285-.042.129 2.904-2.11 2.903 2.11-1.109-3.414 2.904-2.11z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f9 1f1ec';
-->
