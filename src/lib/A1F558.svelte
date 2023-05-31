<script>
  export let size = '36';
  export let ariaLabel = '1f558';
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
  ><circle fill="#99AAB5" cx="18" cy="18" r="18" /><circle
    fill="#E1E8ED"
    cx="18"
    cy="18"
    r="14"
  /><path
    fill="#66757F"
    d="M17 18c0 .553.448 1 1 1 .553 0 1-.447 1-1V7c0-.552-.447-1-1-1-.552 0-1 .448-1 1v11z"
  /><path
    fill="#66757F"
    d="M8 18c0 .552.447 1 1 1h9c.553 0 1-.448 1-1s-.447-1-1-1H9c-.553 0-1 .448-1 1z"
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
