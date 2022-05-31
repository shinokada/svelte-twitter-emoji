
# Svelte-Twemoji

[![npm version](https://badgen.net/npm/v/svelte-twemoji)](https://www.npmjs.com/package/svelte-twemoji)
[![license](https://badgen.net/npm/license/svelte-twemoji)](https://github.com/shinokada/svelte-twemoji/blob/main/LICENSE)

3600+ Twitter emoji SVG color icon components for Svelte. svelte-twemoji support major CSS frameworks using the `class` props.

<p align="center">
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji1.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji2.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji3.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji4.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji5.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji6.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji7.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji8.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji9.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji10.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji11.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-twemoji/main/static/images/twemoji12.png" />
</p>

## Icon name list

[Icon list](https://github.com/shinokada/svelte-twemoji/blob/main/icon-list.md)

## Installation

```sh
npm i -D svelte-twemoji
```

## Usages

In a svelte file:

```html
<script>
	import { A1F1e61f1e8 } from 'svelte-twemoji';
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
	import { A1F1e61f1e8 } from 'svelte-twemoji';
</script>

<svelte:component this="{A1F1e61f1e8}" />
```

## Using onMount

```html
<script>
	import { A1F1e61f1e8 } from 'svelte-twemoji';
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

Use `import * as Icon from 'svelte-twemoji`.

```html
<script>
	import * as Icon from 'svelte-twemoji';
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