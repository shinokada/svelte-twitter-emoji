<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f39a';
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
    fill="#CCD6DD"
    d="M33 32c0 2.209-1.791 4-4 4H7c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h22c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#292F33"
    d="M19 31c0 .553-.448 1-1 1s-1-.447-1-1V5c0-.552.448-1 1-1s1 .448 1 1v26z"
  /><path
    fill="#99AAB5"
    d="M15 6c0 .552-.448 1-1 1h-4c-.552 0-1-.448-1-1s.448-1 1-1h4c.552 0 1 .448 1 1zm0 12c0 .553-.448 1-1 1h-4c-.552 0-1-.447-1-1 0-.552.448-1 1-1h4c.552 0 1 .448 1 1zm0 12c0 .553-.448 1-1 1h-4c-.552 0-1-.447-1-1 0-.553.448-1 1-1h4c.552 0 1 .447 1 1zM27 6c0 .552-.447 1-1 1h-4c-.553 0-1-.448-1-1s.447-1 1-1h4c.553 0 1 .448 1 1zm0 12c0 .553-.447 1-1 1h-4c-.553 0-1-.447-1-1 0-.552.447-1 1-1h4c.553 0 1 .448 1 1zm0 12c0 .553-.447 1-1 1h-4c-.553 0-1-.447-1-1 0-.553.447-1 1-1h4c.553 0 1 .447 1 1zm-12-5.894c0 .494-.4.894-.893.894h-2.214c-.493 0-.893-.4-.893-.894v-.213c0-.493.4-.893.893-.893h2.214c.493 0 .893.4.893.894v.212zm10 0c0 .494-.4.894-.893.894h-2.215c-.492 0-.892-.4-.892-.894v-.213c0-.493.4-.893.893-.893h2.215c.492 0 .892.4.892.894v.212z"
  /><path
    fill="#269"
    d="M25 13c0 1.104-.896 2-2 2H13c-1.104 0-2-.896-2-2v-2c0-1.104.896-2 2-2h10c1.104 0 2 .896 2 2v2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f39a';
-->
