<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f423';
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
    fill="#99AAB5"
    d="M2.75 19.333L5 16l3 3 4-2 3 3 4-6 4 3 3-1 2 3 3-3 2 4-2 7-11 5-11-2-6-6z"
  /><path
    fill="#FFCC4D"
    d="M29.956 14.712c.021-.287.044-.574.044-.866 0-5.943-4.324-10.864-9.996-11.819 1.189-.26 2.031-.509.996-1.027-1.115-.558-2.23.129-2.999.846h-.002C17.23 1.129 16.116.442 15 1c-1.035.518-.193.767.996 1.026C10.325 2.981 6 7.902 6 13.846c0 .292.023.579.044.867C5.562 21.313-.259 31 18 31s12.438-9.687 11.956-16.288z"
  /><path
    fill="#F4900C"
    d="M21 14c0 1.657-1.343 2-3 2s-3-.343-3-2 1.343-3 3-3 3 1.343 3 3z"
  /><circle fill="#662113" cx="11.5" cy="11.5" r="1.5" /><circle
    fill="#662113"
    cx="24.5"
    cy="11.5"
    r="1.5"
  /><path
    fill="#E1E8ED"
    d="M31 25l-3-1-4 6-3-5-2 2-4-2-3 4-3-6-3 2-3.294-7.765C2.249 18.584 2 20.016 2 21.5 2 29.509 9.164 36 18 36s16-6.491 16-14.5c0-1.244-.191-2.444-.517-3.597L31 25z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f423';
-->
