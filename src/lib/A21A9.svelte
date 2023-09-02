<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '21a9';
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
    d="M18 5h-8v4h8.01c3.86.005 6.99 3.137 6.99 7 0 3.865-3.135 7-7 7h-4v-4l-7.2 6 7.2 6v-4h4c6.074 0 11-4.926 11-11 0-6.075-4.926-11-11-11z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '21a9';
-->
