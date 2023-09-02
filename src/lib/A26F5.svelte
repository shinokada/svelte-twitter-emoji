<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '26f5';
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
    fill="#A7A9AC"
    d="M20 26c0 .553-.447 1-1 1-.552 0-1-.447-1-1V1c0-.552.448-1 1-1 .553 0 1 .448 1 1v25z"
  /><path fill="#D1D3D4" d="M3 24h31v8H12c-6 0-9-8-9-8z" /><path
    fill="#55ACEE"
    d="M0 30h36v6H0z"
  /><path fill="#FFAC33" d="M5 22s2-5 5-9 8-8 8-8-1 11-1 16v1s-3-1-6-1-6 1-6 1z" /><path
    fill="#F4900C"
    d="M20 2s6 6 9 11c2.771 4.618 4 9 4 9s-3-1-6-1-6 1-6 1v-1c0-9-1-19-1-19z"
  /><path fill="#E6E7E8" d="M2 24c-.552 0-1 .447-1 1s.448 1 1 1h33v-2H2z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '26f5';
-->
