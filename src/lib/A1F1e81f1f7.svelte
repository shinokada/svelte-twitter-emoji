<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1e8 1f1f7';
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
    fill="#002B7F"
    d="M36 27c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V9c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v18z"
  /><path fill="#EEE" d="M0 9h36v18H0z" /><path fill="#CE1225" d="M0 13h36v10H0z" /><ellipse
    fill="#EEE"
    cx="8.5"
    cy="18"
    rx="3.5"
    ry="4"
  /><path
    fill="#F4CB58"
    d="M10.269 19.5c0 .828-.792 2.079-1.769 2.079S6.731 20.328 6.731 19.5c0-.829.792-1.5 1.769-1.5s1.769.671 1.769 1.5z"
  /><ellipse fill="#DCA841" cx="8.5" cy="19.5" rx="2.5" ry="1.5" /><ellipse
    fill="#89C5E4"
    cx="8.5"
    cy="16"
    rx="1.5"
    ry="1"
  /><ellipse fill="#088930" cx="8.5" cy="18.5" rx="1.5" ry="2.5" /><ellipse
    fill="#DCA841"
    cx="8.5"
    cy="16.5"
    rx="1.5"
    ry=".5"
  /><path
    fill="#89C5E4"
    d="M10 18c0 1.104-.671 2-1.5 2S7 19.104 7 18s.671-1.498 1.5-1.498S10 16.896 10 18z"
  /><ellipse fill="#DCA841" cx="8.5" cy="18.5" rx="1.5" ry=".5" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1e8 1f1f7';
-->
