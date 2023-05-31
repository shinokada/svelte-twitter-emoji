<script>
  export let size = '36';
  export let ariaLabel = '1f1f1 1f1fb';
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
  ><path
    fill="#9E3039"
    d="M32 5H4C1.791 5 0 6.791 0 9v6h36V9c0-2.209-1.791-4-4-4zm0 26H4c-2.209 0-4-1.791-4-4v-6h36v6c0 2.209-1.791 4-4 4z"
  /><path fill="#EEE" d="M0 15h36v6H0z" /></svg
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
