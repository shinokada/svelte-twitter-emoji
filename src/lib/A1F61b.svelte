<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f61b';
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
    fill="#FFCC4D"
    d="M36 18c0 9.941-8.059 18-18 18-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18"
  /><ellipse fill="#66471B" cx="11.5" cy="14.5" rx="2.5" ry="3.5" /><ellipse
    fill="#66471B"
    cx="24.5"
    cy="14.5"
    rx="2.5"
    ry="3.5"
  /><path fill="#66471B" d="M7 21.262c0 3.964 4.596 9 11 9s11-5 11-9c0 0-10.333 2.756-22 0z" /><path
    fill="#E8596E"
    d="M18.545 23.604l-1.091-.005c-3.216-.074-5.454-.596-5.454-.596v6.961c0 3 2 6 6 6s6-3 6-6v-6.92c-1.922.394-3.787.542-5.455.56z"
  /><path
    fill="#DD2F45"
    d="M18 31.843c.301 0 .545-.244.545-.545v-7.694l-1.091-.005v7.699c.001.301.245.545.546.545z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f61b';
-->
