<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f58b';
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
    fill="#99AAB5"
    d="M4.167 32.729c.292.167.626.271.987.271 1.105 0 2-.896 2-2s-.895-2-2-2-2 .896-2 2c0 .361.103.695.27.987L.278 35.133 1.154 28l9-7 5 5-7 9-7.134.876 3.147-3.147z"
  /><path
    fill="#66757F"
    d="M22.511 5.308c-1.151 1.151-1.151 3.016 0 4.167l4.167 4.168c1.151 1.15 3.018 1.15 4.167 0l4.167-4.168c1.15-1.151 1.15-3.016 0-4.167l-4.167-4.167c-1.15-1.151-3.016-1.151-4.167 0l-4.167 4.167z"
  /><path
    fill="#31373D"
    d="M9.511 18.309L26.713 1.105l8.333 8.335-17.201 17.203c-1.15 1.15-3.016 1.15-4.168 0l-4.166-4.168c-1.151-1.151-1.151-3.016 0-4.166z"
  /><path fill="#66757F" d="M17.469 10.35l2.125-2.125 8.334 8.334-2.125 2.125z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f58b';
-->
