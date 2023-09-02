<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f1ec 1f1e6';
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
  ><path fill="#009E60" d="M32 5H4C1.791 5 0 6.791 0 9v5h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#3A75C4"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-5H0v5z"
  /><path fill="#FCD116" d="M0 14h36v8H0z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f1ec 1f1e6';
-->
