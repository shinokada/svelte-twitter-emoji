<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f488';
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
  ><circle fill="#CCD6DD" cx="18" cy="6" r="6" /><path fill="#FFF" d="M11 12h14v21H11z" /><path
    fill="#DD2E44"
    d="M11 28.487L20.251 33H25v-2.134l-14-6.83z"
  /><path fill="#55ACEE" d="M11 19.585l14 6.83v-4.45l-14-6.831z" /><path
    fill="#DD2E44"
    d="M13.697 12L25 17.514V12z"
  /><path
    fill="#99AAB5"
    d="M27 11c0 1.104-.896 2-2 2H11c-1.104 0-2-.896-2-2s.896-2 2-2h14c1.104 0 2 .896 2 2zm0 23c0 1.104-.896 2-2 2H11c-1.104 0-2-.896-2-2s.896-2 2-2h14c1.104 0 2 .896 2 2z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let size = '36';
@prop export let role = 'img';
@prop export let ariaLabel = '1f488';
-->
