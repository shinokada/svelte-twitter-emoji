<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f1 1f1fe';
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
    fill="#141414"
    d="M0 24h36V12H0v12zm21.25-8.298l1.032 1.42 1.67-.542L22.92 18l1.032 1.42-1.67-.542-1.032 1.42v-1.756L19.58 18l1.67-.543v-1.755zM18 14.75c.902 0 1.718.368 2.307.961-.464-.335-1.033-.535-1.649-.535-1.56 0-2.824 1.264-2.824 2.824s1.264 2.824 2.824 2.824c.617 0 1.185-.2 1.649-.535-.589.593-1.405.961-2.307.961-1.795 0-3.25-1.455-3.25-3.25s1.455-3.25 3.25-3.25z"
  /><path fill="#E70013" d="M32 5H4C1.791 5 0 6.791 0 9v3h36V9c0-2.209-1.791-4-4-4z" /><path
    fill="#239E46"
    d="M32 31H4c-2.209 0-4-1.791-4-4v-3h36v3c0 2.209-1.791 4-4 4z"
  /><path
    fill="#FFF"
    d="M18 21.25c.902 0 1.718-.368 2.307-.961-.464.335-1.033.535-1.649.535-1.56 0-2.824-1.264-2.824-2.824s1.264-2.824 2.824-2.824c.617 0 1.185.2 1.649.535-.589-.593-1.405-.961-2.307-.961-1.795 0-3.25 1.455-3.25 3.25s1.455 3.25 3.25 3.25z"
  /><path
    fill="#FFF"
    d="M21.25 18.542v1.756l1.032-1.42 1.67.542L22.92 18l1.032-1.42-1.67.542-1.032-1.42v1.755L19.58 18z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f1 1f1fe';
-->
