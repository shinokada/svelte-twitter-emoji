<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f68b';
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
    fill="#58595B"
    d="M10 32c0-1.657-1.344-3-3-3s-3 1.343-3 3 1.343 3 3 3 3-1.343 3-3z"
  /><path fill="#292F33" d="M9 32c0-1.105-.896-2-2-2s-2 .895-2 2 .896 2 2 2 2-.895 2-2z" /><circle
    fill="#58595B"
    cx="29"
    cy="32"
    r="3"
  /><circle fill="#292F33" cx="29" cy="32" r="2" /><path
    fill="#E6E7E8"
    d="M34 2H2c-.552 0-1-.448-1-1s.448-1 1-1h32c.553 0 1 .448 1 1s-.447 1-1 1z"
  /><path
    fill="#66757F"
    d="M22.998 4.944c-.016-.284-.151-.548-.373-.726l-3.683-2.945c.087-.302.049-.635-.162-.898-.314-.394-.859-.468-1.281-.221-.42-.248-.966-.174-1.281.221-.211.264-.25.597-.162.898l-3.682 2.945c-.222.178-.358.441-.374.726-.016.284.09.561.291.762l3.835 3.834c-.198.377-.152.848.165 1.165.197.197.453.295.709.295.176 0 .344-.063.5-.155.156.091.324.155.5.155.256 0 .512-.098.707-.293.317-.317.363-.788.165-1.165l3.835-3.835c.201-.202.308-.479.291-.763zM17.5 8.085l-3.003-3.003L17.5 2.68l3.003 2.403L17.5 8.085z"
  /><path
    fill="#BCBEC0"
    d="M30 10c0 1.104-.896 2-2 2H8c-1.104 0-2-.896-2-2s.896-2 2-2h20c1.104 0 2 .896 2 2z"
  /><path
    fill="#E6E7E8"
    d="M36 22c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4v-8c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v8zM0 28h36v4H0z"
  /><path fill="#BE1931" d="M0 14h36v14H0z" /><path
    fill="#DD2E44"
    d="M36 14H0v10h6v6h7v-6h10v6h7v-6h6z"
  /><path
    fill="#55ACEE"
    d="M2 16H0v10h2c1.104 0 2-.896 2-2v-6c0-1.104-.896-2-2-2zm34 0h-2c-1.104 0-2 .896-2 2v6c0 1.104.896 2 2 2h2V16zm-15 6c0 .553-.448 1-1 1h-4c-.553 0-1-.447-1-1v-4c0-.553.448-1 1-1h4c.552 0 1 .447 1 1v4zm-9 1c0 .553-.448 1-1 1H8c-.552 0-1-.447-1-1v-5c0-.552.448-1 1-1h3c.552 0 1 .448 1 1v5zm17 0c0 .553-.447 1-1 1h-3c-.553 0-1-.447-1-1v-5c0-.552.447-1 1-1h3c.553 0 1 .448 1 1v5z"
  /><path fill="#A0041E" d="M0 28h36v2H0z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f68b';
-->
