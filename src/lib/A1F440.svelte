<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f440';
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
  ><ellipse fill="#F5F8FA" cx="8.828" cy="18" rx="7.953" ry="13.281" /><path
    fill="#E1E8ED"
    d="M8.828 32.031C3.948 32.031.125 25.868.125 18S3.948 3.969 8.828 3.969 17.531 10.132 17.531 18s-3.823 14.031-8.703 14.031zm0-26.562C4.856 5.469 1.625 11.09 1.625 18s3.231 12.531 7.203 12.531S16.031 24.91 16.031 18 12.8 5.469 8.828 5.469z"
  /><circle fill="#8899A6" cx="6.594" cy="18" r="4.96" /><circle
    fill="#292F33"
    cx="6.594"
    cy="18"
    r="3.565"
  /><circle fill="#F5F8FA" cx="7.911" cy="15.443" r="1.426" /><ellipse
    fill="#F5F8FA"
    cx="27.234"
    cy="18"
    rx="7.953"
    ry="13.281"
  /><path
    fill="#E1E8ED"
    d="M27.234 32.031c-4.88 0-8.703-6.163-8.703-14.031s3.823-14.031 8.703-14.031S35.938 10.132 35.938 18s-3.824 14.031-8.704 14.031zm0-26.562c-3.972 0-7.203 5.622-7.203 12.531 0 6.91 3.231 12.531 7.203 12.531S34.438 24.91 34.438 18 31.206 5.469 27.234 5.469z"
  /><circle fill="#8899A6" cx="25" cy="18" r="4.96" /><circle
    fill="#292F33"
    cx="25"
    cy="18"
    r="3.565"
  /><circle fill="#F5F8FA" cx="26.317" cy="15.443" r="1.426" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f440';
-->
