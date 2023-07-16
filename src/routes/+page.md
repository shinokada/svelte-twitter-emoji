# Svelte Twitter Emoji

<div class="flex gap-2 my-8">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" alt="sponsor" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-twitter-emoji" alt="npm" height="25"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada" height="25"></a>
<a href="https://creativecommons.org/licenses/by/4.0/" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-twitter-emoji" alt="License" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-twitter-emoji.svg" alt="npm" height="25"></a>
</div>

3600+ Twitter emoji SVG color icon components for Svelte.

Thank you for considering my open-source package. If you use it in a commercial project, please support me by sponsoring me on GitHub: https://github.com/sponsors/shinokada. Your support helps me maintain and improve this package for the benefit of the community.

## Repo

[GitHub Repo](https://github.com/shinokada/svelte-twitter-emoji)

## Original source

[twitter/twemoji GitHub Repo](https://github.com/twitter/twemoji)

## License

[Svelte-Twitter-Emoji License](https://github.com/shinokada/svelte-twitter-emoji/blob/main/LICENSE)

[twitter/twemoji LICENSE](https://github.com/twitter/twemoji/blob/master/LICENSE)

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

## Faster compiling

If you need only a few icons from this library in your Svelte app, import them directly. This can optimize compilation speed and improve performance by reducing the amount of code processed during compilation.

```html
<script>
  import A1F1e61f1e8 from 'svelte-twitter-emoji/A1F1e61f1e8.svelte';
</script>

<A1F1e61f1e8 />
```

If you are a TypeScript user, install **typescript version 5.0.0 or above**.

```sh
pnpm i -D typescript@beta
```

To avoid any complaints from the editor, add `node16` or `nodenext` to `moduleResolution` in your tsconfig.json file.

```json
{
  //...
  "compilerOptions": {
    // ...
    "moduleResolution": "nodenext"
  }
}
```

## Props

- size = '36';
- role = 'img';
- ariaLabel = 'icon file name';

## IDE support

If you are using an LSP-compatible editor, such as VSCode, Atom, Sublime Text, or Neovim, hovering over a component name will display a documentation link, features, props, events, and an example.

## Size

Use the `size` prop to change the size of icons.

```html
<A1F1e61f1e8 size="40" />
<A1F1e61f1e8 size="50" />
<A1F1e61f1e8 size="60" />
```

If you are using Tailwind CSS, you can add a custom size using Tailwind CSS by including the desired classes in the class prop. For example:

```html
<A1F1e61f1e8 class="shrink-0 h-20 w-20" />
```

## CSS framworks suport

You can apply CSS framework color and other attributes directly to the icon component or its parent tag using the `class` prop.

Tailwind CSS example:

```html
<Adjust class="h-24 w-24 mr-4" />
```

Bootstrap examples:

```html
<Adjust class="position-absolute top-0 px-1" />
```

## Dark mode

If you are using the dark mode on your website with Tailwind CSS, add your dark mode class to the class prop.

Let’s use dark for the dark mode class as an example.

```html
<Adjust class="text-blue-700 dark:text-red-500" />
```

## aria-label

All icons have aria-label. For example `A1F1e61f1e8` has `aria-label="a1F1e6 1f1e8"`.
Use `ariaLabel` prop to modify the `aria-label` value.

```html
<A1F1e61f1e8 ariaLabel="Twitter emoji" />
```

## Unfocusable icon

If you want to make an icon unfocusable, add `tabindex="-1"`.

```html
<Accessibility16 tabindex="-1" />
```

## Events

All icons have the following events:

- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout

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

[Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)

