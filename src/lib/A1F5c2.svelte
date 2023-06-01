<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f5c2';
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
    fill="#FDCB58"
    d="M31 15c0 1.104-.896 2-2 2H7c-1.104 0-2-.896-2-2V7c0-1.104.896-2 2-2h22c1.104 0 2 .896 2 2v8z"
  /><path
    fill="#FDD888"
    d="M33 19c0 1.104-.896 2-2 2H5c-1.104 0-2-.896-2-2v-8c0-1.104.896-2 2-2h26c1.104 0 2 .896 2 2v8z"
  /><path
    fill="#FEE7B8"
    d="M35 33c0 1.104-.896 2-2 2H3c-1.104 0-2-.896-2-2V15c0-1.104.896-2 2-2h30c1.104 0 2 .896 2 2v18z"
  /><path fill="#67757F" d="M11 14zm0 0z" /><path
    fill="#78B159"
    d="M23 3h-5c-1.104 0-2 .895-2 2v1h2c1.104 0 2 .896 2 2h3c1.104 0 2-.896 2-2V5c0-1.105-.896-2-2-2z"
  /><path
    fill="#F18F26"
    d="M17 7h-5c-1.104 0-2 .896-2 2v1h2c1.104 0 2 .896 2 2h3c1.104 0 2-.896 2-2V9c0-1.104-.896-2-2-2z"
  /><path
    fill="#9268CA"
    d="M13 14c0 1.104-.896 2-2 2H6c-1.104 0-2-.896-2-2v-1c0-1.104.896-2 2-2h5c1.104 0 2 .896 2 2v1z"
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
