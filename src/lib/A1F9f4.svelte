<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f9f4';
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
  ><path fill="#66757F" d="M17 3h2v5h-2z" /><path
    fill="#99AAB5"
    d="M12 12V9c0-1.1.9-2 2-2h8c1.1 0 2 .9 2 2v3H12z"
  /><path
    fill="#FFAC33"
    d="M24 11H12c-5 0-6 21-6 21 0 2.2 1.8 4 4 4h16c2.2 0 4-1.8 4-4 0 0-1-21-6-21z"
  /><path fill="#CCD6DD" d="M8 4s2-4 7-4h6c2 0 2 4 0 4h-6c-5 0-6 1-6 1L8 4z" /><path
    fill="#99AAB5"
    d="M8.464 4.464L9 5s1-1 6-1h6c.975 0 1.472-.949 1.496-1.922C21 2.078 19.524 2 15 2c-3.859 0-5.519 1.377-6.536 2.464z"
  /><path
    fill="#FFCC4D"
    d="M23.5 13h-11c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h11c.275 0 .5.225.5.5s-.225.5-.5.5z"
  /><path fill="#FFE8B6" d="M18 18s-4 4.791-4 7c0 2.209 1.791 4 4 4s4-1.791 4-4-4-7-4-7z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f9f4';
-->
