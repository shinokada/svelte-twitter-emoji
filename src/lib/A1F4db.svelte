<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f4db';
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
    d="M28.303 2.576c-.449-.317-1.017-.173-1.263.319l-2.595 5.21c-.245.492-.695.521-1.001.064L18.556.86c-.306-.457-.806-.457-1.112 0l-4.888 7.308c-.306.457-.757.428-1.002-.064L8.96 2.895c-.245-.492-.813-.636-1.263-.319C7.697 2.576 0 8 0 20c0 7.732 8.059 16 18 16s18-8.268 18-16c0-12-7.697-17.424-7.697-17.424z"
  /><path
    fill="#F5F8FA"
    d="M32 23c0 1.104-.896 2-2 2H6c-1.104 0-2-.896-2-2v-7c0-1.104.896-2 2-2h24c1.104 0 2 .896 2 2v7z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f4db';
-->
