<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f31c';
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
    fill="#FFD983"
    d="M11 13c0-4.984 1.934-9.505 5.073-12.894C7.039 1.068 0 8.71 0 18c0 9.941 8.06 18 18 18 4.303 0 8.25-1.515 11.348-4.033-7.164-.245-13.306-4.451-16.351-10.484-.622-1.232 2.795-1.201 2.962-3.482C16.113 15.87 11 15.26 11 13"
  /><g fill="#FFCC4D"
    ><circle cx="10.5" cy="28.5" r="3.5" /><circle cx="9" cy="7" r="1" /><circle
      cx="18"
      cy="32"
      r="1"
    /><circle cx="3" cy="20" r="2" /></g
  ><path
    d="M16.203 26.023c-.775-.819-1.48-1.705-2.104-2.651-5.449 1.226-7.637-.273-7.316.807.341 1.147 4.797 3.008 9.42 1.844M10 14.5c0 1.381-1.12 2.5-2.5 2.5S5 15.881 5 14.5 6.12 12 7.5 12s2.5 1.119 2.5 2.5"
    fill="#292F33"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f31c';
-->
