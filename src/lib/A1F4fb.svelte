<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4fb';
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
    fill="#292F33"
    d="M2.697 12.389c-.391.391-.391 1.023 0 1.414s1.023.391 1.414 0l9.192-9.192c.391-.391.391-1.023 0-1.414s-1.023-.391-1.414 0l-9.192 9.192z"
  /><path fill="#99AAB5" d="M36 32c0 4-4 4-4 4H4s-4 0-4-4V14s0-4 4-4h28c4 0 4 4 4 4v18z" /><path
    fill="#292F33"
    d="M15.561 3.061c-.391.391-1.023.391-1.414 0l-.707-.707c-.391-.391-.391-1.023 0-1.414s1.023-.391 1.414 0l.707.707c.39.39.39 1.023 0 1.414z"
  /><circle fill="#292F33" cx="27.5" cy="18.5" r="5.5" /><circle
    fill="#292F33"
    cx="27.5"
    cy="29.5"
    r="3.5"
  /><circle fill="#66757F" cx="27.5" cy="18.5" r="3.5" /><circle
    fill="#66757F"
    cx="27.5"
    cy="29.5"
    r="1.5"
  /><g fill="#292F33"
    ><circle cx="10.5" cy="25.5" r="1.5" /><circle cx="5.5" cy="25.5" r="1.5" /><circle
      cx="10.5"
      cy="20.5"
      r="1.5"
    /><circle cx="15.5" cy="20.5" r="1.5" /><circle cx="15.5" cy="25.5" r="1.5" /><circle
      cx="15.5"
      cy="30.5"
      r="1.5"
    /><circle cx="5.5" cy="30.5" r="1.5" /><circle cx="5.5" cy="20.5" r="1.5" /><circle
      cx="10.5"
      cy="15.5"
      r="1.5"
    /><circle cx="15.5" cy="15.5" r="1.5" /><circle cx="5.5" cy="15.5" r="1.5" /><circle
      cx="10.5"
      cy="30.5"
      r="1.5"
    /></g
  ></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4fb';
-->
