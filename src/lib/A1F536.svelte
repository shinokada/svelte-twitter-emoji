<script>
  export let size = '36';
  export let ariaLabel = '1f536';
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
    fill="#F4900C"
    d="M1.061 19.062c-.583-.584-.583-1.539 0-2.122L16.94 1.061c.583-.583 1.539-.583 2.122 0L34.94 16.94c.583.583.583 1.538 0 2.121L19.062 34.939c-.583.583-1.539.583-2.122 0L1.061 19.062z"
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
