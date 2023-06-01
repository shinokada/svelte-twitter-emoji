<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f1f8 1f1f9';
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
    fill="#12AD2B"
    d="M32 5H4C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h28c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4z"
  /><path fill="#FFCE00" d="M8.173 13.5H36v9H8.173z" /><path
    fill="#D21034"
    d="M1.149 6.195C.438 6.917 0 7.907 0 9v18c0 1.093.438 2.083 1.148 2.805L12.5 18 1.149 6.195z"
  /><path
    d="M18.004 20.36l1.625-1.181 1.624 1.181-.62-1.91 1.624-1.181h-2.008l-.62-1.909-.621 1.909H17l1.625 1.181zm9.5 0l1.625-1.181 1.624 1.181-.62-1.91 1.624-1.181h-2.008l-.62-1.909-.621 1.909H26.5l1.625 1.181z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop size = '36';
@prop role = 'img';
@prop ariaLabel = 'icon file name';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
