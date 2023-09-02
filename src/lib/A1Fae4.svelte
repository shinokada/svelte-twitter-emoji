<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1fae4';
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
  xml:space="preserve"
  ><path
    fill="#FFCC4D"
    d="M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18 8.059 0 18 0s18 8.059 18 18"
  /><ellipse fill="#65471B" cx="11.5" cy="15.5" rx="2.5" ry="3.5" /><ellipse
    fill="#65471B"
    cx="24.5"
    cy="15.5"
    rx="2.5"
    ry="3.5"
  /><path
    fill="#65471B"
    d="m11.209 27.978 14-3a1.001 1.001 0 0 0-.419-1.957l-14 3a1.001 1.001 0 0 0 .419 1.957z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1fae4';
-->
