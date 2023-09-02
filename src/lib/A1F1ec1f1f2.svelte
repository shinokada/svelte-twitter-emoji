<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f1ec 1f1f2';
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
  ><path fill="#CC162B" d="M32 5H4C1.791 5 0 6.791 0 9v4h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#3C762C"
    d="M0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-4H0v4z"
  /><path fill="#EEE" d="M0 21h36v2H0zm0-8h36v2H0z" /><path fill="#0D218A" d="M0 15h36v6H0z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f1ec 1f1f2';
-->
