<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f37d';
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
    fill="#E1E8ED"
    d="M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18 8.059 0 18 0s18 8.059 18 18z"
  /><path
    fill="#CCD6DD"
    d="M30 18c0 6.628-5.372 12-12 12S6 24.628 6 18 11.372 6 18 6s12 5.372 12 12z"
  /><path
    fill="#E1E8ED"
    d="M29 18c0 6.075-4.925 11-11 11-6.076 0-11-4.925-11-11 0-6.076 4.925-11 11-11s11 4.924 11 11z"
  /><g fill="#99AAB5"
    ><circle cx="1" cy="1" r="1" /><path d="M0 1h2v7H0z" /><circle cx="5" cy="1" r="1" /><path
      d="M4 1h2v7H4z"
    /><circle cx="9" cy="1" r="1" /><path d="M8 1h2v7H8zM3 14h4v20H3z" /><circle
      cx="5"
      cy="34"
      r="2"
    /><path
      d="M8 8c0 .552-.448 1-1 1s-1-.448-1-1H4c0 .552-.448 1-1 1s-1-.448-1-1H0c0 3.866 1 7 5 7s5-3.134 5-7H8z"
    /><circle cx="1" cy="8" r="1" /><circle cx="5" cy="8" r="1" /><circle cx="9" cy="8" r="1" /></g
  ><g fill="#99AAB5"
    ><path d="M30 14h4v20h-4z" /><circle cx="32" cy="34" r="2" /><path
      d="M32 0c1 0 2 1 2 3v16s-7 2-7-8c0-6 3-11 5-11z"
    /></g
  ></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f37d';
-->
