<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1ed 1f1f3';
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
  ><path fill="#EEE" d="M0 14h36v8H0z" /><path
    fill="#0156A3"
    d="M32 5H4C1.791 5 0 6.791 0 9v5h36V9c0-2.209-1.791-4-4-4zM0 27c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4v-5H0v5z"
  /><path
    fill="#2657A7"
    d="M18.265 17.76l-.249-.766-.249.766h-.806l.652.473-.249.767.652-.474.652.474-.249-.767.652-.473zm5.332 2.48l-.249.766.652-.473.652.473-.249-.766.652-.473h-.806L24 19l-.249.767h-.806zm.652-4.48L24 14.994l-.249.766h-.806l.652.473-.249.767.652-.474.652.474-.249-.767.652-.473zm-12.707 4.48l-.249.766.652-.473.652.473-.249-.766.652-.473h-.806L11.945 19l-.249.767h-.806zm.652-4.48l-.249-.766-.249.766h-.806l.652.473-.249.767.652-.474.652.474-.249-.767.652-.473z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1ed 1f1f3';
-->
