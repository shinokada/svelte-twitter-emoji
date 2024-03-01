<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6aa';
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
    fill="#BF6952"
    d="M29 34c0 1.105-.895 2-2 2H9c-1.105 0-2-.895-2-2V2c0-1.105.895-2 2-2h18c1.105 0 2 .895 2 2v32z"
  /><circle fill="#FFAC33" cx="11" cy="18" r="1.5" /><path
    fill="#AC5640"
    d="M25 3c-.552 0-1 .448-1 1v9H11c-.552 0-1 .448-1 1s.448 1 1 1h14c.552 0 1-.448 1-1V4c0-.552-.448-1-1-1zm0 25c.552 0 1 .448 1 1v3c0 .552-.448 1-1 1H11c-.552 0-1-.448-1-1s.448-1 1-1h13v-2c0-.552.448-1 1-1z"
  /><path
    fill="#854836"
    d="M11 33c-.552 0-1-.448-1-1v-3c0-.552.448-1 1-1h14c.552 0 1 .448 1 1s-.448 1-1 1H12v2c0 .552-.448 1-1 1z"
  /><path
    fill="#AC5640"
    d="M25 21c.552 0 1 .448 1 1v3c0 .552-.448 1-1 1H11c-.552 0-1-.448-1-1s.448-1 1-1h13v-2c0-.552.448-1 1-1z"
  /><path
    fill="#854836"
    d="M11 26c-.552 0-1-.448-1-1v-3c0-.552.448-1 1-1h14c.552 0 1 .448 1 1s-.448 1-1 1H12v2c0 .552-.448 1-1 1zm0-11c-.552 0-1-.448-1-1V4c0-.552.448-1 1-1h14c.552 0 1 .448 1 1s-.448 1-1 1H12v9c0 .552-.448 1-1 1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6aa';
-->
