<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '203c';
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
  ><circle fill="#BE1931" cx="11" cy="31" r="3" /><path
    fill="#BE1931"
    d="M14 23c0 1.657-1.343 3-3 3s-3-1.343-3-3V4c0-1.657 1.343-3 3-3s3 1.343 3 3v19z"
  /><circle fill="#BE1931" cx="25" cy="31" r="3" /><path
    fill="#BE1931"
    d="M28 23c0 1.657-1.344 3-3 3s-3-1.343-3-3V4c0-1.657 1.344-3 3-3s3 1.343 3 3v19z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '203c';
-->
