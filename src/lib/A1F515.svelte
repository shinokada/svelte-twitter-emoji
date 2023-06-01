<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f515';
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
    fill="#FFAC33"
    d="M28 13c0 11 5 10 5 15 0 0 0 2-2 2H5c-2 0-2-2-2-2 0-5 5-4 5-15C8 7.478 12.477 3 18 3s10 4.478 10 10z"
  /><circle fill="#FFAC33" cx="18" cy="3" r="3" /><path
    fill="#FFAC33"
    d="M18 36c2.209 0 4-1.791 4-4h-8c0 2.209 1.791 4 4 4z"
  /><path
    fill="#DD2E44"
    d="M31.003 33.003L3.997 5.997c-.551-.551-.551-1.443 0-1.994l.006-.006c.551-.551 1.443-.551 1.994 0l27.006 27.006c.551.551.551 1.443 0 1.994l-.006.006c-.551.551-1.443.551-1.994 0z"
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
