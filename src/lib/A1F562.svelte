<script>
  export let size = '36';
  export let ariaLabel = '1f562';
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
    d="M17 29c0 .553.447 1 1 1 .553 0 1-.447 1-1V18c0-.552-.447-1-1-1-.553 0-1 .448-1 1v11z"
  /><path
    fill="#66757F"
    d="M13 26.661c.479.276 1.09.112 1.367-.366l4.5-7.795c.275-.478.111-1.089-.367-1.365s-1.089-.112-1.365.365l-4.5 7.795c-.277.478-.112 1.09.365 1.366z"
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
