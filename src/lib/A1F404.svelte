<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f404';
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
    fill="#CCD6DD"
    d="M34 15c0-2-2.127-4.702-4-4-8 3-19-2-19-2-2.209 0-6.857 9.257-5 10 .277.111.541.227.799.343C4.648 20.087 4.283 21.809 6 22c9 1 6.896 14 8 14 1.344 0 2.685-2.614 3.422-5h9.8c.288 2.354.866 5 1.778 5 .866 0 2.611-3.542 3.794-9.142C33.528 24.232 34 20.326 34 15z"
  /><path
    fill="#31373D"
    d="M10 22c-2 0-4.946.087-6.973.087S-.617 18.609.692 17.305C2 16 6 15 5 11c-.542-2.169 4-3 6-2 4.816 2.408 5 10-2 10 0 0 3 3 1 3zm20-11c-2.586.97-5.485 1.101-8.226.838C20.669 13.231 20 15.031 20 17c0 4.418 3.357 8 7.5 8 2.587 0 4.866-1.396 6.215-3.521.181-1.872.285-4.017.285-6.479 0-2-2.127-4.702-4-4z"
  /><circle fill="#31373D" cx="17.5" cy="24.5" r="3.5" /><circle
    fill="#31373D"
    cx="30"
    cy="28"
    r="2"
  /><path
    fill="#CCD6DD"
    d="M11 9c0 .552-.671 1-1.5 1S5 7.552 5 7s2.23-.308 3 0c2.5 1 3 1.448 3 2z"
  /><circle fill="#CCD6DD" cx="8" cy="13" r="1" /><path
    fill="#31373D"
    d="M35 24c-.553 0-1-.447-1-1v-5c0-1.44-.561-2-2-2-.553 0-1-.448-1-1s.447-1 1-1c2.542 0 4 1.458 4 4v5c0 .553-.447 1-1 1z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f404';
-->
