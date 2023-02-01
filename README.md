<h1 align="center">Svelte Twitter Emoji</h1>

<p align="center">
<a href="https://svelte-twitter-emoji.codewithshin.com/">Svelte-Twitter-Emoji</a>
</p>

<p align="center">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" height="25"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps" target="_blank"><img src="https://img.shields.io/badge/PWA-enabled-brightgreen" alt="PWA Shield" height="25">
</a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-twitter-emoji" alt="npm" height="25"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada" height="25"></a>
<a href="https://creativecommons.org/licenses/by/4.0/" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-twitter-emoji" alt="License" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-twitter-emoji.svg" alt="npm" height="25"></a>
</p>

3600+ Twitter emoji SVG color icon components for Svelte. svelte-twitter-emoji support major CSS frameworks using the `class` props.

<p align="center">
<img width="650" src="/static/images/twitter-emoji-optimized-650-1050.png" />
</p>

## Installation

```sh
npm i -D svelte-twitter-emoji
```

## Icon name list

All files has A before a number. For example `1F004` becomes `A1F004`.

Find out icons from file name at [Emoji catalog](https://projects.iamcal.com/emoji-data/table.htm)

[Icon list](/icon-list.md)

## Icon images

[Icon images](/icon-images.md)

## Usages

In a svelte file:

```html
<script>
  import { A1F1e61f1e8 } from 'svelte-twitter-emoji';
</script>

<A1F1e61f1e8 />
```

## Size

Use the `size` prop to change the size of icons.

```html
<A1F1e61f1e8 size="40" />
<A1F1e61f1e8 size="50" />
<A1F1e61f1e8 size="60" />
```

## CSS framworks suport

Use the `class` prop to change size, colors and add additional css.

Tailwind CSS example:

```html
<Adjust class="h-24 w-24 mr-4" />
```

Bootstrap examples:

```html
<Adjust class="position-absolute top-0 px-1" />
```

## aria-label

All icons have aria-label. For example `A1F1e61f1e8` has `aria-label="a1F1e6 1f1e8"`.
Use `ariaLabel` prop to modify the `aria-label` value.

```html
<A1F1e61f1e8 ariaLabel="Twitter emoji" />
```

## Passing down other attributes

You can pass other attibutes as well.

```html
<A1F1e61f1e8 tabindex="0" />
```

## Using svelte:component

```html
<script>
  import { A1F1e61f1e8 } from 'svelte-twitter-emoji';
</script>

<svelte:component this="{A1F1e61f1e8}" />
```

## Using onMount

```html
<script>
  import { A1F1e61f1e8 } from 'svelte-twitter-emoji';
  import { onMount } from 'svelte';
  const props = {
    size: '50',
    color: '#ff0000'
  };
  onMount(() => {
    const icon = new A1F1e61f1e8({ target: document.body, props });
  });
</script>
```

## Import all

Use `import * as Icon from 'svelte-twitter-emoji`.

```html
<script>
  import * as Icon from 'svelte-twitter-emoji';
</script>

<Icon.A1F1e61f1e8 />
<Icon.A1F1f21f1f9 />

<h1>Size</h1>
<Icon.A1F1e61f1e8 size="30" />
<Icon.A1F1f21f1f9 size="40" />

<h1>Tailwind CSS</h1>
<Icon.A1F1e61f1e8 class="px-2" />
<Icon.A1F1f21f1f9 class="mr-2" />
```

## Attribution

Original SVG souce by [twitter/twemoji](https://github.com/twitter/twemoji)-[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)

## PWA: Fast & Offline

This website can be downloaded and installed on your device for offline access as a Progressive Web App.

To install a PWA, look for the "Add to Home Screen" option in the browser's menu or settings. On most mobile devices, this option can be found by visiting the website, then selecting the "Options" or "Menu" button in the browser, and looking for the "Add to Home Screen" option. On some desktop browsers, right-click on the page and select "Install".
