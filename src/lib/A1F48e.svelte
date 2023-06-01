<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f48e';
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
  ><path fill="#BDDDF4" d="M13 3H7l-7 9h10z" /><path fill="#5DADEC" d="M36 12l-7-9h-6l3 9z" /><path
    fill="#4289C1"
    d="M26 12h10L18 33z"
  /><path fill="#8CCAF7" d="M10 12H0l18 21zm3-9l-3 9h16l-3-9z" /><path
    fill="#5DADEC"
    d="M18 33l-8-21h16z"
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
