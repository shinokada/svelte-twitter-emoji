<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f9c8';
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
    d="M35.145 22.16l-22.86 13.219c-.902.521-2.364.521-3.266 0L.855 30.658c-.451-.261-.676-.602-.676-.944v-1.843l23.535-12.32c.902-.521 2.364-.521 3.266 0l8.84 3.819c0 .558-.005 1.497 0 1.834.006.345-.219.692-.675.956z"
  /><path
    fill="#CCD6DD"
    d="M35.145 20.344l-22.86 13.219c-.902.521-2.364.521-3.266 0L.855 28.842c-.902-.521-.902-1.367 0-1.888l22.86-13.219c.902-.521 2.364-.521 3.266 0l8.164 4.721c.901.521.901 1.367 0 1.888z"
  /><path fill="#FFE8B6" d="M33 19.011v-8.083l-7-4.041-13.042 7.502v8.083l7 4.042z" /><path
    fill="#FFD983"
    d="M33 19.011v-8.083l-13.042 7.503-7-4.042v8.083l7 4.042z"
  /><path fill="#FFCC4D" d="M33 19.011v-8.083l-13.042 7.503v8.083z" /><path
    fill="#FFE8B6"
    d="M17.182 28.302V26.29l-7-4.041L3 26.325v2.012l7 4.041z"
  /><path fill="#FFD983" d="M17.182 28.302V26.29l-7 4.059L3 26.325v2.012l7 4.041z" /><path
    fill="#FFCC4D"
    d="M17.182 28.302V26.29l-7 4.059L10 32.378z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f9c8';
-->
