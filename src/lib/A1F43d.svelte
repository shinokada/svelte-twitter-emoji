<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f43d';
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
    fill="#E6AAAA"
    d="M35 18c0 6.075-4.925 11-11 11H12C5.925 29 1 24.075 1 18S5.925 7 12 7h12c6.075 0 11 4.925 11 11z"
  /><ellipse fill="#662113" cx="10" cy="18" rx="4" ry="6" /><ellipse
    fill="#662113"
    cx="26"
    cy="18"
    rx="4"
    ry="6"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f43d';
-->
