<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f972';
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
  ><circle fill="#FFCC4D" cx="18" cy="18" r="18" /><ellipse
    fill="#664500"
    cx="12"
    cy="13.5"
    rx="2.5"
    ry="3.5"
  /><ellipse fill="#664500" cx="24" cy="13.5" rx="2.5" ry="3.5" /><path
    fill="#664500"
    d="M27.335 22.629c-.178-.161-.444-.171-.635-.029-.039.029-3.922 2.9-8.7 2.9-4.766 0-8.662-2.871-8.7-2.9-.191-.142-.457-.13-.635.029-.177.16-.217.424-.094.628C8.7 23.472 11.788 28.5 18 28.5s9.301-5.028 9.429-5.243c.123-.205.084-.468-.094-.628z"
  /><path
    fill="#5DADEC"
    d="M29.5 27.5c0 2.762-2.238 5-5 5s-5-2.238-5-5 4-10 5-10 5 7.238 5 10z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f972';
-->
