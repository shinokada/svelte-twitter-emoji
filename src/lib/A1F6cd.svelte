<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f6cd';
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
    fill="#F4900C"
    d="M11 0C6.582 0 3 3.582 3 8v8h2V8c0-3.313 2.687-6 6-6 3.314 0 6 2.687 6 6v8h2V8c0-4.418-3.582-8-8-8z"
  /><path fill="#DD2E44" d="M1 8l2 2 2-2 2 2 2-2 2 2 2-2 2 2 2-2 2 2 2-2v23H1z" /><path
    fill="#FFCC4D"
    d="M25 5c-4.418 0-8 3.582-8 8v8h2v-8c0-3.314 2.688-6 6-6 3.315 0 6 2.686 6 6v8h2v-8c0-4.418-3.582-8-8-8z"
  /><path fill="#744EAA" d="M15 13l2 2 2-2 2 2 2-2 2 2 2-2 2 2 2-2 2 2 2-2v23H15z" /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f6cd';
-->
