<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f58d';
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
    fill="#DD2E44"
    d="M35.702 7.477L28.522.298c-.396-.397-1.038-.397-1.436 0L3.395 23.989c-.397.397-.397 1.038 0 1.437.72.719-3.14 7.959-3.395 8.496L2.068 36c.536-.255 7.785-4.115 8.506-3.395.397.397 1.039.397 1.436 0L35.702 8.913c.397-.396.397-1.039 0-1.436z"
  /><path fill="#EA596E" d="M4.139 23.24L26.407.972l8.62 8.62L12.759 31.86z" /><path
    fill="#292F33"
    d="M23.534 3.846l1.437-1.436 8.62 8.62-1.437 1.436zM5.576 21.803l1.436-1.437 8.62 8.62-1.437 1.437z"
  /><path
    fill="#BE1931"
    d="M26.886 9.353c-1.521-1.521-5.982.476-9.967 4.459-3.983 3.984-5.979 8.446-4.459 9.967 1.52 1.521 5.983-.476 9.967-4.459 3.983-3.984 5.979-8.447 4.459-9.967z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f58d';
-->
