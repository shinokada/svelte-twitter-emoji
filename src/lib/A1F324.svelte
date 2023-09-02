<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f324';
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
    fill="#FFAC33"
    d="M16 2s0-2 2-2 2 2 2 2v2s0 2-2 2-2-2-2-2V2zm18 14s2 0 2 2-2 2-2 2h-2s-2 0-2-2 2-2 2-2h2zM4 16s2 0 2 2-2 2-2 2H2s-2 0-2-2 2-2 2-2h2zm5.121-8.707s1.414 1.414 0 2.828-2.828 0-2.828 0L4.878 8.708s-1.414-1.414 0-2.829c1.415-1.414 2.829 0 2.829 0l1.414 1.414zm20.587 2.828s-1.414 1.414-2.828 0 0-2.828 0-2.828l1.414-1.414s1.414-1.414 2.828 0 0 2.828 0 2.828l-1.414 1.414zm-21 21s-1.414 1.414-2.828 0 0-2.828 0-2.828l1.414-1.414s1.414-1.414 2.828 0 0 2.828 0 2.828l-1.414 1.414z"
  /><circle fill="#FFAC33" cx="18" cy="18" r="10" /><path
    fill="#E1E8ED"
    d="M29.777 23.2c-.642 0-1.26.1-1.843.285-.688-2.028-2.56-3.485-4.767-3.485-2.368 0-4.35 1.678-4.899 3.937-.586-.456-1.309-.736-2.101-.736-1.933 0-3.5 1.611-3.5 3.6 0 .483.096.941.264 1.363-.334-.097-.679-.164-1.042-.164C9.741 28 8 29.791 8 32s1.741 4 3.889 4h17.889C33.214 36 36 33.136 36 29.6c0-3.535-2.786-6.4-6.223-6.4z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f324';
-->
