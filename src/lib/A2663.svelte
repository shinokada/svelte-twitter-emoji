<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '2663';
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
    fill="#31373D"
    d="M25.5 28c4.143 0 7.5-3.358 7.5-7.5 0-4.142-3.357-7.5-7.5-7.5-1.359 0-2.631.367-3.73 1h-.21c2.047-1.217 3.423-3.445 3.423-6 0-3.857-3.126-6.984-6.983-6.984S11.016 4.143 11.016 8c0 2.555 1.376 4.783 3.423 6h-.208c-1.1-.633-2.371-1-3.731-1C6.358 13 3 16.358 3 20.5c0 4.142 3.358 7.5 7.5 7.5 2.155 0 4.091-.914 5.46-2.368C15.549 29.753 11.205 33 7 33h.5c-.829 0-1.5.672-1.5 1.5S6.671 36 7.5 36h21c.828 0 1.5-.672 1.5-1.5s-.672-1.5-1.5-1.5h.5c-4.205 0-8.549-3.248-8.959-7.369C21.408 27.086 23.346 28 25.5 28z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '2663';
-->
