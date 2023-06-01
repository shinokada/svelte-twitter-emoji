<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f361';
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
    fill="#D99E82"
    d="M33.875 35.228c-.314 0-.628-.12-.868-.359L2.366 4.227c-.479-.479-.479-1.257 0-1.736s1.257-.479 1.736 0l30.641 30.641c.479.479.479 1.257 0 1.736-.24.239-.554.36-.868.36z"
  /><path
    fill="#FCB1E3"
    d="M15.254 8.627c0 3.729-3.023 6.752-6.752 6.752-3.729 0-6.752-3.023-6.752-6.752 0-3.729 3.023-6.752 6.752-6.752 3.729 0 6.752 3.023 6.752 6.752z"
  /><ellipse
    transform="rotate(-76.714 15.87 15.994)"
    fill="#FFD983"
    cx="15.869"
    cy="15.994"
    rx="6.752"
    ry="6.752"
  /><path
    fill="#A6D388"
    d="M29.987 23.359c0 3.729-3.024 6.753-6.753 6.753s-6.752-3.024-6.752-6.753 3.023-6.752 6.752-6.752 6.753 3.024 6.753 6.752z"
  /><path
    fill="#D99E82"
    d="M33.875 35.228c-.314 0-.628-.12-.868-.359l-7.52-7.52c-.48-.479-.48-1.257 0-1.736.48-.479 1.256-.479 1.736 0l7.52 7.52c.479.479.479 1.257 0 1.736-.24.238-.554.359-.868.359z"
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
