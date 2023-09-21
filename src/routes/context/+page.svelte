<script>
  import { setContext } from 'svelte';
  import { A3297, A26C4 } from '$lib';
  const iconCtx = {
    size: '100', // Icon size in pixels
    color: '#00ff00', // Icon color in hexadecimal or CSS color name
    role: 'svg icon image'
  };
  setContext('iconCtx', iconCtx);
</script>

<A3297 />
<A26C4 />
