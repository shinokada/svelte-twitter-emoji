<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f3b1';
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
  ><circle fill="#31373D" cx="18" cy="18" r="18" /><circle
    fill="#E1E8ED"
    cx="18"
    cy="18"
    r="9"
  /><path
    fill="#31373D"
    d="M13.703 20.203c0-1.406.773-2.443 1.881-3.041-.826-.598-1.336-1.406-1.336-2.514 0-2.057 1.705-3.375 3.797-3.375 2.039 0 3.814 1.301 3.814 3.375 0 .984-.492 1.969-1.354 2.514 1.195.598 1.881 1.688 1.881 3.041 0 2.443-1.986 4.008-4.342 4.008-2.425 0-4.341-1.652-4.341-4.008zm2.742-.176c0 .896.527 1.758 1.6 1.758 1.002 0 1.6-.861 1.6-1.758 0-1.107-.633-1.758-1.6-1.758-1.02.001-1.6.774-1.6 1.758zm.334-5.097c0 .791.457 1.336 1.266 1.336.809 0 1.283-.545 1.283-1.336 0-.756-.457-1.336-1.283-1.336-.826 0-1.266.58-1.266 1.336z"
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
