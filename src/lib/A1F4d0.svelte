<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f4d0';
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
    d="M35.106 33.172L2.828.894C1.273-.662 0-.135 0 2.065V32c0 2.2 1.8 4 4 4h29.935c2.2 0 2.727-1.272 1.171-2.828zM16.967 28H10c-1.1 0-2-.9-2-2v-6.968c0-1.1.637-1.363 1.414-.586l8.139 8.14c.777.777.513 1.414-.586 1.414z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop size = '36';
@prop role = 'img';
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
