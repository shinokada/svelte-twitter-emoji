<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f637';
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
    fill="#FFCC4D"
    d="M36 18c0 9.941-8.059 18-18 18-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18"
  /><path
    fill="#664500"
    d="M7.001 15c-.323 0-.64-.156-.833-.445-.306-.46-.182-1.081.277-1.387C6.578 13.08 9.746 11 14 11c.552 0 1 .448 1 1s-.448 1-1 1c-3.655 0-6.418 1.814-6.445 1.832-.171.114-.364.168-.554.168zm21.998 0c-.189 0-.382-.054-.552-.167C28.419 14.815 25.628 13 22 13c-.553 0-1-.448-1-1s.447-1 1-1c4.254 0 7.422 2.08 7.555 2.168.46.306.584.927.277 1.387-.192.289-.51.445-.833.445z"
  /><path
    fill="#F5F8FA"
    d="M27 22.091L36 18c0-.66-.041-1.309-.109-1.95L27 20.091V19c0-1.104-.896-2-2-2H11c-1.104 0-2 .896-2 2v1.091L.11 16.05C.041 16.691 0 17.34 0 18l9 4.091v4.546l-7.453-1.355c.341.77.741 1.507 1.183 2.215L9 28.637V30c0 1.104.896 2 2 2h14c1.104 0 2-.896 2-2v-1.363l6.271-1.141c.441-.708.841-1.445 1.182-2.215L27 26.637v-4.546z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f637';
-->
