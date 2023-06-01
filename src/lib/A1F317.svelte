<script>
  export let size = '36';
  export let role = 'img';
  export let ariaLabel = '1f317';
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
  ><path fill="#FFD983" d="M18 0v36C8.059 36 0 27.941 0 18S8.059 0 18 0z" /><path
    fill="#66757F"
    d="M36 18c0 9.941-8.059 18-18 18V0c9.941 0 18 8.059 18 18z"
  /><circle fill="#FFCC4D" cx="10.5" cy="8.5" r="3.5" /><circle
    fill="#5B6876"
    cx="24"
    cy="16"
    r="3"
  /><circle fill="#5B6876" cx="22.5" cy="27.5" r="3.5" /><circle
    fill="#5B6876"
    cx="21"
    cy="6"
    r="2"
  /><circle fill="#FFCC4D" cx="3" cy="18" r="1" /><circle
    fill="#5B6876"
    cx="30"
    cy="9"
    r="1"
  /><circle fill="#FFCC4D" cx="15" cy="31" r="1" /><circle
    fill="#5B6876"
    cx="32"
    cy="19"
    r="2"
  /><circle fill="#FFCC4D" cx="10" cy="23" r="2" /></svg
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
