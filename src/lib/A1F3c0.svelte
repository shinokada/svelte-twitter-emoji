<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3c0';
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
  ><circle fill="#F4900C" cx="18" cy="18" r="18" /><path
    fill="#231F20"
    d="M36 17h-8.981c.188-5.506 1.943-9.295 4.784-10.546-.445-.531-.926-1.027-1.428-1.504-2.83 1.578-5.145 5.273-5.354 12.049H19V0h-2v17h-6.021c-.208-6.776-2.523-10.471-5.353-12.049-.502.476-.984.972-1.428 1.503C7.039 7.705 8.793 11.494 8.981 17H0v2h8.981c-.188 5.506-1.942 9.295-4.783 10.546.445.531.926 1.027 1.428 1.504 2.831-1.578 5.145-5.273 5.353-12.05H17v17h2V19h6.021c.209 6.776 2.523 10.471 5.354 12.05.502-.476.984-.973 1.428-1.504-2.841-1.251-4.595-5.04-4.784-10.546H36v-2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3c0';
-->
