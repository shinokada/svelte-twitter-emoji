<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3ef';
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
  ><path fill="#D1D3D4" d="M5 23h26v7H5z" /><path fill="#D99E82" d="M0 36h36l-4-7H4z" /><path
    fill="#66757F"
    d="M30 20H6l-5 4h34z"
  /><path fill="#D1D3D4" d="M18 9.882L9.764 14h16.472z" /><path
    fill="#66757F"
    d="M30 14l-1-5H7l-1 5-4 3h32l-4-3zM18 9.882L26.236 14H9.764L18 9.882z"
  /><path fill="#D1D3D4" d="M6 17h24v3H6zm18-8V5H12v4h-2v2h16V9z" /><path
    fill="#66757F"
    d="M12 2h12v2l2 2H10l2-2z"
  /><path fill="#99AAB5" d="M23 0v1H13V0h-1v2h12V0z" /><path
    fill="#66757F"
    d="M30 14.764l-5.105-2.553-6-3L18 8.764l-.895.447-6 3L6 14.764V16h24v-1.236zM12 14l6-3 6 3H12z"
  /><path fill="#6D6E71" d="M5 27h26v2H5z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3ef';
-->
