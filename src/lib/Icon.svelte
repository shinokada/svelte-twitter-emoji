<script lang="ts">
  import type { ComponentType } from 'svelte';
  export let icon: ComponentType;
  export let size: number = 30;
  export let role: string = 'img';
  export let ariaLabel = 'Icon';
</script>

<svelte:component this={icon} {...$$restProps} {role} {size} class={$$props.class} {ariaLabel} />

<!--
@component
[Go to docs](https://svelte-twitter-emoji.vercel.app/)
## Props
@prop export let icon: ComponentType;
@prop export let size: number = 30;
@prop export let role: string = 'img';
@prop export let ariaLabel = 'Icon';
-->
