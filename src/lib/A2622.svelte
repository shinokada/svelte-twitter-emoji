<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '2622';
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
  ><circle fill="#F4900C" cx="18" cy="18" r="17" /><path
    fill="#FFF"
    d="M15.272 21.598l-3.85 6.427c.278.183.561.36.854.519C13.978 29.472 15.929 30 18 30c2.078 0 4.033-.532 5.739-1.464.293-.16.576-.336.854-.519l-3.855-6.427c-.763.583-1.704.942-2.738.942-1.029 0-1.967-.356-2.728-.934zm.847-7.71l-3.854-6.425c-.293.16-.577.336-.854.52-3.124 2.062-5.22 5.543-5.385 9.518-.008.166-.026.33-.026.499s.018.333.025.5h7.493c-.018-.166-.05-.329-.05-.5 0-1.829 1.09-3.396 2.651-4.112zM22.532 18c0 .171-.032.334-.05.5h7.493c.007-.167.025-.331.025-.5s-.018-.333-.025-.5c-.165-3.974-2.26-7.454-5.382-9.516-.278-.183-.561-.359-.854-.52l-3.85 6.427c1.556.718 2.643 2.282 2.643 4.109z"
  /><circle fill="#FFF" cx="18" cy="18" r="2" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '2622';
-->
