<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f1eb 1f1ee';
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
  ><path fill="#EDECEC" d="M32 5H18v10h18V9c0-2.209-1.791-4-4-4z" /><path
    fill="#EEE"
    d="M11 5H4C1.791 5 0 6.791 0 9v6h11V5z"
  /><path
    fill="#EDECEC"
    d="M32 31H18V21h18v6c0 2.209-1.791 4-4 4zm-21 0H4c-2.209 0-4-1.791-4-4v-6h11v10z"
  /><path fill="#003580" d="M18 5h-7v10H0v6h11v10h7V21h18v-6H18z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f1eb 1f1ee';
-->
