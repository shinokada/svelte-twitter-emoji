<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f6a4';
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
  ><path fill="#5C913B" d="M33 27h-2l1-8h2z" /><path
    fill="#DD2E44"
    d="M1 14c9.055.053 11 1 17 2 2.959.493 7 1 11 1 2 0 4 1 4 4 0 2 .534 3.187-5.433 3.815C23.59 25.233 13 23 9 21c-6-3-9-7.005-8-7z"
  /><path fill="#55ACEE" d="M0 24h36v12H0z" /><path
    fill="#FFCC4D"
    d="M5 13c4 0 11 0 18 1s10 1 10 3v3c0 1.414-6.869.447-10 0-7-1-14-3-18-4-4.047-1.011-7-3 0-3z"
  /><path
    fill="#A0041E"
    d="M30.592 24.322c2.122-.539 2.403-1.307 2.418-2.361-1.263.619-3.699.32-5.886.047-7.96-.995-16.481-2.935-24.722-5.608 1.043 1.04 2.584 2.29 4.568 3.483 6.706 1.901 13.484 3.307 19.905 4.109 1.259.157 2.53.312 3.717.33z"
  /><path
    fill="#55ACEE"
    d="M12 24c3-2 7-5 6-3s-1.001 3 1 2c2-1 5-2 4 0s2 1 3 0 4 0 3 1-9 2-12 2-5-2-5-2z"
  /><path
    fill="#5C913B"
    d="M34 16h-1c-1.104 0-2 .896-2 2h1c.553 0 1 .447 1 1v1h1c1.104 0 2 .104 2-1s-.896-3-2-3z"
  /><path fill="#C1694F" d="M30 16c.97.243 0 2-1 3s-10-1-10-1l2-3s5 0 9 1z" /><path
    fill="#A0041E"
    d="M29 19c.328-.328.645-.737.899-1.147-1.475-.764-3.63-1.385-6.079-1.664-1.249-.142-2.441-.178-3.527-.128L19 18s9 2 10 1z"
  /><path fill="#55ACEE" d="M21 15v-1l-4 1-2 2 4 1z" /><path
    fill="#292F33"
    d="M23 14c-.553 0-1 1.343-1 3 0 .612.062 1.181.167 1.656.502.127 1.035.221 1.592.278.148-.524.241-1.193.241-1.934 0-1.656-.447-3-1-3z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f6a4';
-->
