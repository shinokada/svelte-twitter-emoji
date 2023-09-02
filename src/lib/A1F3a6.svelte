<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f3a6';
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
    fill="#3B88C3"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M21 11c0 3.314-2.687 6-6 6-3.314 0-6-2.686-6-6s2.686-6 6-6c3.313 0 6 2.686 6 6zm10.999 2c0 2.761-2.239 5-5 5s-5-2.239-5-5 2.239-5 5-5 5 2.238 5 5z"
  /><path
    fill="#FFF"
    d="M30 20c0-2.209-1.791-4-4-4H15c-2.209 0-4 1.791-4 4l-6-4H4v13h1l6-4v2c0 2.209 1.791 4 4 4h11c2.209 0 4-1.791 4-4v-7z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f3a6';
-->
