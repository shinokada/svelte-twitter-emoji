<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f316';
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
    fill="#FFD983"
    d="M0 18c0 9.941 8.059 18 18 18 .295 0 .58-.029.87-.043C24.761 33.393 29 26.332 29 18 29 9.669 24.761 2.607 18.87.044 18.58.03 18.295 0 18 0 8.059 0 0 8.059 0 18z"
  /><path
    fill="#66757F"
    d="M29 18C29 9.669 24.761 2.607 18.87.044 28.404.501 36 8.353 36 18c0 9.646-7.594 17.498-17.128 17.956C24.762 33.391 29 26.331 29 18z"
  /><circle fill="#FFCC4D" cx="10.5" cy="8.5" r="3.5" /><circle
    fill="#FFCC4D"
    cx="20"
    cy="16"
    r="3"
  /><circle fill="#FFCC4D" cx="21.5" cy="27.5" r="3.5" /><circle
    fill="#FFCC4D"
    cx="21"
    cy="6"
    r="2"
  /><circle fill="#FFCC4D" cx="3" cy="18" r="1" /><circle
    fill="#5B6876"
    cx="30"
    cy="9"
    r="1"
  /><circle fill="#FFCC4D" cx="15" cy="31" r="1" /><circle
    fill="#5B6876"
    cx="32"
    cy="19"
    r="2"
  /><circle fill="#FFCC4D" cx="10" cy="23" r="2" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f316';
-->
