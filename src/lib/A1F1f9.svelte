<script>
  export let size = '36';
  export let ariaLabel = '1f1f9';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  class={$$props.class}
  {...$$restProps}
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
    fill="#3B88C3"
    d="M36 32c0 2.209-1.791 4-4 4H4c-2.209 0-4-1.791-4-4V4c0-2.209 1.791-4 4-4h28c2.209 0 4 1.791 4 4v28z"
  /><path
    fill="#FFF"
    d="M15.676 11.203h-3.38c-1.488 0-2.108-1.085-2.108-2.139 0-1.085.775-2.14 2.108-2.14h11.411c1.332 0 2.108 1.054 2.108 2.14 0 1.054-.619 2.139-2.108 2.139h-3.381v15.565c0 1.551-.992 2.418-2.325 2.418-1.333 0-2.325-.867-2.325-2.418V11.203z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop size = '36';
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
