<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let ariaLabel = '1f3a3';
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
    fill="#CCD6DD"
    d="M8 16c-.552 0-1-.448-1-1V4c0-.552.448-1 1-1s1 .448 1 1v11c0 .552-.448 1-1 1z"
  /><path
    fill="#3B88C3"
    d="M2 33c0-2.236 4-6 7-6v5c-1 0-4 1-5 2s-2 0-2-1zm14 0c0-2.236-4-6-7-6v5c1 0 4 1 5 2s2 0 2-1z"
  /><path
    fill="#3B88C3"
    d="M15 14c2 0 4 1 4 2 0 3-3.167 11.542-8.167 12.542S15 14 15 14zM3 20c-1 1-2 3-2 5s2.75-2.042 4-1c1.718 1.432-2-4-2-4z"
  /><path
    d="M5.583 12.25c1.5.5 2.583.125 3.667-.75s1.25 2.542-.25 3.667-4.125 3.75-4.083 1.417c.041-2.334.666-4.334.666-4.334z"
  /><path
    fill="#55ACEE"
    d="M9.023 11.001c-.574.63-1.856 2.332-2.481 4.415-.875.5-.833-1.208-.708-1.75.225-.975.506-.977.346-1.521-.21-.551-.789-.364-1.119-.159C3.348 12.97 2 14.8 2 18c0 5.522 5 13 7 13s7-7.478 7-13c0-5.509-3.979-6.992-6.977-6.999z"
  /><circle cx="11.5" cy="15.5" r="1.5" /><path
    fill="#269"
    d="M8.954 22.827c-1.504 0-2.829-.538-4-1.149-.49-.256-.679-.86-.423-1.35.255-.488.859-.68 1.349-.424 1.891.988 3.59 1.385 5.735.11.475-.281 1.088-.124 1.37.35.282.476.125 1.089-.35 1.371-1.334.792-2.558 1.092-3.681 1.092z"
  /><path
    fill="#662113"
    d="M29.834 35.25c-.494-.247-1.042-.958-.729-1.697 1.334-3.146 4.278-16.9 1.604-24.761-.501-1.472-2.118-3.659-4.08-4.863C20.292.042 10.823 2.171 9.5 2.833c-.495.248-2.044.744-2.292.25-.247-.494.589-1.003 1.083-1.25 1.756-.877 11.264-3.878 19.667.791 1.5.833 3.59 2.376 4.703 5.303 3.257 8.567 1.047 23.416-.787 26.822-.582 1.084-1.896.572-2.04.501z"
  /><circle fill="#99AAB5" cx="28" cy="25" r="4" /><circle
    fill="#66757F"
    cx="28"
    cy="25"
    r="2"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-twitter-emoji.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let ariaLabel = '1f3a3';
-->
