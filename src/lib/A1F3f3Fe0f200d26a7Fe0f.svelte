<script>
  export let size = '36';
  export let ariaLabel = '1f3f3 fe0f 200d 26a7 fe0f';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  class={$$props.class}
  {...$$restProps}
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
  ><path fill="#5BCEFA" d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-1.3H0V27z" /><path
    fill="#F5A9B8"
    d="M.026 20.5L0 25.8h36v-5.3z"
  /><path fill="#EEE" d="M0 15.3h36v5.3H0z" /><path fill="#F5A9B8" d="M0 9.902h36V15.4H0z" /><path
    fill="#5BCEFA"
    d="M36 9c0-2.209-1.791-4-4-4H4C1.791 5 0 6.791 0 9v1.2h36V9z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop size = '36';
@prop ariaLabel = 'icon file name';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
