<script>
  export let size = '36';
  export let ariaLabel = '1f3f4 e0067 e0062 e0073 e0063 e0074 e007f';
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
    fill="#EEE"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path
    d="M13 18S0 8.586 0 8.895v18.21C0 27.414 13 18 13 18zm5 3S3.697 31 4.07 31h27.859C32.303 31 18 21 18 21zm5-3s13 9.414 13 9.105V8.895C36 8.586 23 18 23 18zm-5-3S3.697 5 4.07 5h27.859C32.303 5 18 15 18 15z"
    fill="#0065BD"
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
