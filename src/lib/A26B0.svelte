<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '26b0';
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
  ><path fill="#C1694F" d="M31 12l-1.412 10.235L7.353 36 5 28z" /><path
    fill="#662113"
    d="M1 22v7.647L7.353 36v-8z"
  /><path fill="#A04E3C" d="M34 5v7.706l-4.412 9.529V15L31 9z" /><path
    fill="#D99E82"
    d="M34 5l-4.412 9.824L7.353 28.588 1 22 17.941 2.118 28.529 0z"
  /><path
    fill="#FFAC33"
    d="M12.001 30c-.323 0-.64-.156-.833-.445-.306-.46-.182-1.08.277-1.387l3-2c.459-.307 1.08-.183 1.387.277.306.46.182 1.08-.277 1.387l-3 2c-.171.113-.364.168-.554.168zm11-7c-.323 0-.641-.156-.833-.445-.307-.46-.183-1.08.277-1.387l3-2c.461-.306 1.08-.182 1.387.277.307.46.183 1.08-.277 1.387l-3 2c-.171.113-.364.168-.554.168z"
  /><path
    fill="#C1694F"
    d="M9 25c-.258 0-.514-.1-.708-.293l-3-3c-.382-.382-.392-.997-.022-1.391l15-16c.15-.16.349-.266.565-.302l6-1c.315-.054.642.05.871.279l2 2c.284.283.371.707.223 1.079l-2 5c-.07.176-.189.328-.343.439l-18 13C9.41 24.938 9.205 25 9 25zm-1.608-4.022l1.713 1.713L26.18 10.359l1.646-4.119-1.169-1.17-5.159.86L7.392 20.978z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '26b0';
-->
