<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f4f2';
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
  ><path fill="#31373D" d="M18 36s-4 0-4-4V4s0-4 4-4h14s4 0 4 4v28s0 4-4 4H18z" /><path
    fill="#55ACEE"
    d="M16 5h18v26H16zm-3 11s1 1 1 2-1 2-1 2l-5 5c-1 1-3 1-3-1v-3H2s-2 0-2-2v-2c0-2 2-2 2-2h3v-3c0-2 2-2 3-1l5 5z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop size = '36';
@prop role = 'img';
@prop ariaLabel = 'icon file name';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
