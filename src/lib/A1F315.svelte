<script>
  export let size = '36';
  export let ariaLabel = '1f315';
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
  ><circle fill="#FFD983" cx="18" cy="18" r="18" /><g fill="#FFCC4D"
    ><circle cx="10.5" cy="8.5" r="3.5" /><circle cx="20" cy="17" r="3" /><circle
      cx="24.5"
      cy="28.5"
      r="3.5"
    /><circle cx="22" cy="5" r="2" /><circle cx="3" cy="18" r="1" /><circle
      cx="30"
      cy="9"
      r="1"
    /><circle cx="15" cy="31" r="1" /><circle cx="32" cy="19" r="2" /><circle
      cx="10"
      cy="23"
      r="2"
    /></g
  ></svg
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
