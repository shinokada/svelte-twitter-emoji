<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f476 1f3ff';
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
    fill="#7C533E"
    d="M36 18.5c0-1.639-.97-3.004-2.273-3.385C32.367 7.658 25.85 2 18 2 10.15 2 3.633 7.658 2.273 15.115.97 15.496 0 16.861 0 18.5c0 1.736 1.087 3.168 2.51 3.442C4.269 28.868 10.527 34 18 34c7.473 0 13.731-5.132 15.49-12.058C34.912 21.668 36 20.236 36 18.5z"
  /><path d="M18 25c-3 0-4-1-4 1s2 4 4 4 4-2 4-4-1-1-4-1z" /><circle
    cx="22.5"
    cy="18.5"
    r="2.5"
  /><circle cx="13.5" cy="18.5" r="2.5" /><path
    fill="#FFF"
    d="M18 26h2v1s0 1-1 1-1-1-1-1v-1z"
  /><path
    fill="#543226"
    d="M17.982 11h-.031c-1.188 0-2.301-.458-3.135-1.304-.746-.756-1.138-1.787-1.076-2.847.032-.551.49-.96 1.057-.935.551.033.972.508.939 1.06-.029.495.155.983.503 1.336.459.466 1.071.725 1.725.729.653-.036 1.27-.247 1.735-.705 1.298-1.28 1.312-3.378.032-4.677-1.699-1.721-4.48-1.74-6.202-.042-.394.389-1.027.383-1.414-.01-.388-.393-.383-1.026.01-1.414 2.506-2.472 6.557-2.444 9.03.062 2.055 2.084 2.031 5.432-.052 7.486-.836.826-1.945 1.261-3.121 1.261z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f476 1f3ff';
-->
