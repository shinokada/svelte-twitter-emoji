<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f1f3 1f1f5';
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
  ><path fill="#22408B" d="M27.796 19L8 5v26h19.796L15.918 19z" /><path
    fill="#DD2F45"
    d="M25 18L9 7.196V30h16L13.574 18z"
  /><path
    fill="#FFF"
    d="M14.291 24.041l.586-.816-1 .098.1-1-.817.586-.414-.916-.414.916-.817-.586.099 1-1-.098.586.816-.916.414.916.414-.586.816 1-.098-.099 1 .817-.586.414.916.414-.916.817.586-.1-1 1 .098-.586-.816.916-.414zm-1.546-7.147l.001.002.001-.002.018.002c1.468 0 2.66-1.13 2.784-2.567-.348.648-.912 1.16-1.595 1.442l-.175-.244.611-.276-.611-.276.391-.545-.668.066.067-.668-.546.391-.276-.612-.276.612-.546-.391.067.668-.668-.066.391.545-.611.276.611.276-.167.233c-.67-.284-1.222-.792-1.566-1.431.121 1.429 1.303 2.554 2.763 2.565z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f1f3 1f1f5';
-->
