<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1fa9c';
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
    d="M26 21H10c-.552 0-1 .448-1 1v1c0 .552.448 1 1 1h16c.552 0 1-.448 1-1v-1c0-.552-.448-1-1-1z"
  /><path fill="#662113" d="M10 22.5h16V24H10z" /><path
    fill="#D99E82"
    d="M26 13H10c-.552 0-1 .448-1 1v1c0 .552.448 1 1 1h16c.552 0 1-.448 1-1v-1c0-.552-.448-1-1-1z"
  /><path fill="#662113" d="M10 14.5h16V16H10z" /><path
    fill="#D99E82"
    d="M26 5H10c-.552 0-1 .448-1 1v1c0 .552.448 1 1 1h16c.552 0 1-.448 1-1V6c0-.552-.448-1-1-1zm0 24H10c-.552 0-1 .448-1 1v1c0 .552.448 1 1 1h16c.552 0 1-.448 1-1v-1c0-.552-.448-1-1-1z"
  /><path fill="#662113" d="M10 6.5h16V8H10zm0 24h16V32H10z" /><path
    fill="#D99E82"
    d="M8 35h2c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1H8c-.55 0-1 .45-1 1v32c0 .55.45 1 1 1z"
  /><path
    fill="#662113"
    d="M10 35c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1v32c0 .55.45 1 1 1z"
  /><path
    fill="#BF6952"
    d="M26.043 35h2c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1v32c0 .55.45 1 1 1z"
  /><path
    fill="#662113"
    d="M28.043 35c.55 0 1-.45 1-1V2c0-.55-.45-1-1-1s-1 .45-1 1v32c0 .55.45 1 1 1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1fa9c';
-->
