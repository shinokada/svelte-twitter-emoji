<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4ad';
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
    fill="#BDDDF4"
    d="M35 12c0-3.866-3.134-7-7-7-1.167 0-2.265.29-3.232.794-2.082-2.827-5.425-4.669-9.205-4.669-5.132 0-9.475 3.38-10.923 8.036C1.982 9.778 0 12.155 0 15c0 2.979 2.174 5.445 5.021 5.913C5.237 24.862 8.498 28 12.5 28c2.176 0 4.13-.933 5.5-2.413C19.37 27.067 21.323 28 23.5 28c4.143 0 7.5-3.357 7.5-7.5 0-.71-.105-1.394-.289-2.045C33.23 17.396 35 14.905 35 12z"
  /><circle fill="#BDDDF4" cx="4" cy="31" r="3" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4ad';
-->
