<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f538';
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
    fill="#F4900C"
    d="M7.707 18.708c-.389-.389-.389-1.025 0-1.414l9.585-9.586c.389-.389 1.025-.389 1.414 0l9.587 9.587c.389.389.389 1.025 0 1.414l-9.587 9.585c-.389.389-1.025.389-1.414 0l-9.585-9.586z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f538';
-->
