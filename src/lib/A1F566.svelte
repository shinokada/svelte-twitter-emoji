<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f566';
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
    d="M13 9.34c-.479.276-.643.888-.366 1.367l4.5 7.793c.276.479.888.643 1.367.367.478-.276.642-.889.365-1.367l-4.5-7.793c-.277-.479-.889-.643-1.366-.367z"
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
