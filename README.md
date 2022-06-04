# svelte-twitter-emoji

[![npm version](https://badgen.net/npm/v/svelte-twitter-emoji)](https://www.npmjs.com/package/svelte-twitter-emoji)
[![license](https://badgen.net/npm/license/svelte-twitter-emoji)](https://github.com/shinokada/svelte-twitter-emoji/blob/main/LICENSE)

3600+ Twitter emoji SVG color icon components for Svelte. svelte-twitter-emoji support major CSS frameworks using the `class` props.

<p align="center">
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji1.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji2.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji3.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji4.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji5.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji6.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji7.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji8.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji9.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji10.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji11.webp" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twitter-emoji/main/static/images/twemoji12.webp" />
</p>

## Attribution

Original SVG souce by [twitter/twemoji](https://github.com/twitter/twemoji)-[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Icon name list

All files has A before a number. For example `1F004` becomes `A1F004`.

Find out icons from file name at [Emoji catalog](https://projects.iamcal.com/emoji-data/table.htm)

[Icon list](https://github.com/shinokada/svelte-twitter-emoji/blob/main/icon-list.md)

## Installation

```sh
npm i -D svelte-twitter-emoji
```

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

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)
