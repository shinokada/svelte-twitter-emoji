<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '2757';
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
  ><circle fill="#BE1931" cx="18" cy="32" r="3" /><path
    fill="#BE1931"
    d="M21 24c0 1.657-1.344 3-3 3-1.657 0-3-1.343-3-3V5c0-1.657 1.343-3 3-3 1.656 0 3 1.343 3 3v19z"
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
