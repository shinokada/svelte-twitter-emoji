<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '21aa';
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
    fill="#3B88C3"
    d="M0 32c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V4c0-2.209-1.791-4-4-4H4C1.791 0 0 1.791 0 4v28z"
  /><path
    fill="#FFF"
    d="M29.2 25L22 19v4h-4c-3.865 0-7-3.135-7-7 0-3.866 3.135-7 7-7h8V5h-8C11.926 5 7 9.925 7 16c0 6.074 4.926 11 11 11h4v4l7.2-6z"
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
