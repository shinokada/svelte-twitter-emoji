<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f457';
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
    fill="#55ACEE"
    d="M22.42 11.847L26 2s-.398.002-1 .034V0h-2v2.219c-2.271.302-5 1.028-5 2.781 0-1.753-2.729-2.479-5-2.781V0h-2v2.034C10.398 2.002 10 2 10 2l3.581 9.847L1 25.643S7 36 18 36s17-10.357 17-10.357L22.42 11.847z"
  /><path fill="#BBDDF5" d="M13 11h10v2H13z" /><path
    fill="#3B88C3"
    d="M15 13s-6.734 8.106-5.051 9.006C11.633 22.907 15 13 15 13zm6.096 0s6.734 8.105 5.051 9.007c-1.684.9-5.051-9.007-5.051-9.007zM18 13s-2 11 0 11 0-11 0-11z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f457';
-->
