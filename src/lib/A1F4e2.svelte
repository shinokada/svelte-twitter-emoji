<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4e2';
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
    fill="#BE1931"
    d="M12.908 30.75c-.276 2.209-2.291 3-4.5 3s-3.776-1.791-3.5-4l1-9c.276-2.209 2.291-4 4.5-4s6.468 0 3.5 4-1 10-1 10z"
  /><path
    fill="#CCD6DD"
    d="M35.825 14.75c0 6.902-1.544 12.5-3.45 12.5-1.905 0-20.45-5.598-20.45-12.5 0-6.903 18.545-12.5 20.45-12.5 1.906 0 3.45 5.597 3.45 12.5z"
  /><ellipse fill="#66757F" cx="32.375" cy="14.75" rx="3.45" ry="12.5" /><path
    fill="#DD2E44"
    d="M17.925 21.75l-14-1c-5 0-5-12 0-12l14-1c-3 3-3 11 0 14z"
  /><ellipse fill="#99AAB5" cx="31.325" cy="14.75" rx="1.5" ry="4.348" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4e2';
-->
