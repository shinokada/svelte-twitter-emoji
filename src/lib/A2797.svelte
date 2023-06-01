<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '2797';
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
    fill="#31373D"
    d="M34 18c0 1.657-1.343 3-3 3H5c-1.657 0-3-1.343-3-3s1.343-3 3-3h26c1.657 0 3 1.343 3 3z"
  /><circle fill="#31373D" cx="18" cy="7" r="4" /><circle
    fill="#31373D"
    cx="18"
    cy="29"
    r="4"
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
