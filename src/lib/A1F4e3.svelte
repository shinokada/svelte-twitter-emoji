<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f4e3';
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
    d="M14 19c-3.314 0-6 2.687-6 6s2.686 6 6 6 6-2.687 6-6-2.687-6-6-6zm0 10c-2.209 0-4-1.791-4-4s1.791-4 4-4 4 1.791 4 4-1.791 4-4 4z"
  /><path
    fill="#55ACEE"
    d="M1.783 14.023v.02C.782 14.263 0 15.939 0 18s.782 3.737 1.783 3.956v.021l28.701 7.972V6.064L1.783 14.023z"
  /><ellipse fill="#269" cx="31" cy="18" rx="5" ry="12" /></svg
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
