<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f69f';
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
    fill="#58595B"
    d="M30 16c0 1.104-.896 2-2 2H18c-1.104 0-2-.896-2-2v-2c0-1.104.896-2 2-2h10c1.104 0 2 .896 2 2v2z"
  /><path fill="#F4900C" d="M4 14c-2.209 0-4 1.791-4 4v10c0 4.418 3.582 8 8 8h28V14H4z" /><path
    fill="#FFD983"
    d="M.587 31H36v-2H.069c.087.698.263 1.369.518 2z"
  /><path fill="#808285" d="M0 2h36v6H0z" /><path fill="#414042" d="M0 4h36v2H0z" /><path
    fill="#A7A9AC"
    d="M28 0H18c-1.657 0-3 1.343-3 3s1.343 3 3 3h3v4l-2 2h8l-2-2V6h3c1.657 0 3-1.343 3-3s-1.343-3-3-3z"
  /><path fill="#3B88C3" d="M14 14h22v15H14z" /><path
    fill="#58595B"
    d="M12 25c0 1.104-.896 2-2 2H6c-1.104 0-2-.896-2-2v-6c0-1.104.896-2 2-2h4c1.104 0 2 .896 2 2v6z"
  /><path
    fill="#414042"
    d="M24 23c0 1.104-.896 2-2 2h-4c-1.104 0-2-.896-2-2v-4c0-1.104.896-2 2-2h4c1.104 0 2 .896 2 2v4zm10 0c0 1.104-.896 2-2 2h-4c-1.104 0-2-.896-2-2v-4c0-1.104.896-2 2-2h4c1.104 0 2 .896 2 2v4z"
  /><path fill="#58595B" d="M0 17v10c1.104 0 2-.896 2-2v-6c0-1.104-.896-2-2-2z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f69f';
-->
