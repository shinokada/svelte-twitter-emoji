<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f963';
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
  ><path fill="#A0041E" d="M16 31c8.837 0 16-7.163 16-16H0c0 8.837 7.164 16 16 16z" /><ellipse
    fill="#EA596E"
    cx="16"
    cy="15"
    rx="16.051"
    ry="8.917"
  /><ellipse fill="#662113" cx="16" cy="15" rx="14.641" ry="7.719" /><path
    fill="#99AAB5"
    d="M34 8c-1 0-4 1-8 4-4.525 3.394-7.596 2.187-7.596 2.187l.001.003C16.981 13.453 15.087 13 13 13c-4.418 0-8 2.015-8 4.5S8.582 22 13 22c2.773 0 5.216-.794 6.651-2 0 0 4.995-4.431 7.349-6 3-2 5-3 7-3s2-3 0-3z"
  /><ellipse fill="#CCD6DD" cx="13" cy="19" rx="5" ry="2.5" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f963';
-->
