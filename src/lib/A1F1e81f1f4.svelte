<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f1e8 1f1f4';
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
  ><path fill="#FBD116" d="M32 5H4C1.791 5 0 6.791 0 9v9h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#22408C"
    d="M0 18h36v7H0z"
  /><path fill="#CE2028" d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-2H0v2z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f1e8 1f1f4';
-->
