<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3cf';
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
    d="M35.538 26.679s1.328 2.214-2.658 6.201c-3.987 3.986-6.201 2.658-6.201 2.658L7.185 16.046s.977-2.748 3.544-5.316c2.568-2.567 5.316-3.544 5.316-3.544l19.493 19.493z"
  /><path
    fill="#C1694F"
    d="M13.388 9.844c.979.979 4.522 6.109 3.544 7.088-.979.978-6.109-2.565-7.088-3.544l-8.86-8.86C.006 3.549.006 1.963.984.984c.979-.978 2.565-.978 3.544 0l8.86 8.86z"
  /><path fill="#292F33" d="M.983 4.528L4.528.984 9.844 6.3 6.3 9.844z" /><circle
    fill="#BE1931"
    cx="19"
    cy="31"
    r="5"
  /><path
    fill="#662113"
    d="M19 36c-.552 0-1-.447-1-1v-8c0-.553.448-1 1-1 .553 0 1 .447 1 1v8c0 .553-.447 1-1 1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3cf';
-->
