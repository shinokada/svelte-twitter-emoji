<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f2 1f1fb';
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
    fill="#D21034"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path fill="#007E3A" d="M6 11h24v14H6z" /><path
    fill="#FFF"
    d="M19.64 22.344c.279 0 .551-.027.814-.077-2.009-.381-3.529-2.146-3.529-4.266s1.52-3.885 3.529-4.266c-.264-.05-.536-.077-.814-.077-2.399 0-4.344 1.945-4.344 4.344 0 2.397 1.945 4.342 4.344 4.342z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f2 1f1fb';
-->
