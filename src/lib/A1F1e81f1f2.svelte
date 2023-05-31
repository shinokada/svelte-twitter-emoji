<script>
  export let size = '36';
  export let ariaLabel = '1f1e8 1f1f2';
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
    fill="#CC212D"
    d="M12 5v26h12V5H12zm7.882 15.59L18 19.223l-1.882 1.367.719-2.212-1.882-1.367h2.326L18 14.798l.719 2.212h2.326l-1.882 1.367.719 2.213z"
  /><path fill="#288541" d="M4 5C1.791 5 0 6.791 0 9v18c0 2.209 1.791 4 4 4h8V5H4z" /><path
    fill="#FEE833"
    d="M32 5h-8v26h8c2.209 0 4-1.791 4-4V9c0-2.209-1.791-4-4-4zM18.719 17.011L18 14.798l-.719 2.213h-2.326l1.882 1.367-.719 2.212L18 19.223l1.882 1.367-.719-2.212 1.882-1.367z"
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
