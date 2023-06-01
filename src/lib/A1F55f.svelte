<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f55f';
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
    fill="#67757F"
    d="M18 31c-.552 0-1-.447-1-1V18c0-.552.448-1 1-1 .553 0 1 .448 1 1v12c0 .553-.447 1-1 1z"
  /><path
    fill="#67757F"
    d="M24.999 24c-.201 0-.404-.06-.58-.187l-7-5c-.45-.321-.554-.945-.233-1.395.321-.45.946-.554 1.395-.233l7 5c.449.32.554.945.232 1.395-.195.274-.501.42-.814.42z"
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
