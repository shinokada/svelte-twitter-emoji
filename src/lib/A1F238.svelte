<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f238';
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
    fill="#F4900C"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M16.746 6.789c0-.494.39-.78 1.014-.78s1.014.286 1.014.78v2.938h7.125c1.691 0 2.392.676 2.392 2.288v9.751c0 1.611-.701 2.314-2.392 2.314h-7.125v5.277c0 .52-.39.779-1.014.779s-1.014-.26-1.014-.779V24.08H10.09c-1.69 0-2.392-.703-2.392-2.314v-9.751c0-1.612.702-2.288 2.392-2.288h6.656V6.789zm-5.981 4.757c-.858 0-1.092.26-1.092.962v3.25h7.072v-4.212h-5.98zm-1.092 6.033v3.718c0 .703.234.963 1.092.963h5.981v-4.681H9.673zm16.642-1.82v-3.25c0-.702-.261-.962-1.093-.962h-6.448v4.212h7.541zm-1.093 6.501c.832 0 1.093-.26 1.093-.963v-3.718h-7.541v4.681h6.448z"
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
