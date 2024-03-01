---
layout: mainLayout
---

# Svelte Twitter Emoji

<div class="flex gap-2 my-8">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" alt="sponsor"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-twitter-emoji" alt="npm"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada"></a>
<a href="https://creativecommons.org/licenses/by/4.0/" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-twitter-emoji" alt="License"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-twitter-emoji.svg" alt="npm"></a>
</div>

3600+ Twitter emoji SVG color icon components for Svelte.

Thank you for considering my open-source package. If you use it in a commercial project, please support me by sponsoring me on GitHub: https://github.com/sponsors/shinokada. Your support helps me maintain and improve this package for the benefit of the community.

## Repo

[GitHub Repo](https://github.com/shinokada/svelte-twitter-emoji)

## Installation

```sh
pnpm i -D svelte-twitter-emoji
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

## Props

- size = ctx.size || '24';
- role = ctx.role || 'img';
- ariaLabel = 'file name';

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

## Setting Global Icon using setContext

You can establish global icon preferences in your Svelte application using `setContext`. This allows you to configure icon-related properties once and share them across multiple components. Here's how you can do it:

```html
<script>
  import { setContext } from 'svelte';

  // Define your global icon settings
  const iconCtx = {
    strokeWidth: '1.5',
    size: '100', // Icon size in pixels
    color: '#ff4488', // Icon color in hexadecimal or CSS color name
    role: 'svg icon image' // Accessible role for the icon
  };
  setContext('iconCtx', iconCtx);
</script>
```

The `size`, `ariaLabel` and `role` properties are optional, allowing you to fine-tune the appearance and accessibility of your icons as needed.

If you set `size`, icons can be customized with different colors. For example:

```html
<script>
  import { setContext } from 'svelte';
  import { A26C4 } from 'svelte-twitter-emoji';
  const iconCtx = {
    size: '50'
  };
  setContext('iconCtx', iconCtx);
</script>

<A26C4 ariaLabel="christmas image" />
```

Remember that you can set only one or two of these properties, allowing you to tailor icon settings to your specific design and accessibility requirements.

Feel free to mix and match these properties as needed to create visually appealing and accessible icons in your Svelte application.

## Creating a Default Icon Setting

You can create a config file, `/src/lib/icon.config.json`.

The `Icon` component serves as a wrapper for svelte:component, allowing you to establish a global default setting or expand the capabilities of a component.

To create a default global icon setting, follow these steps:

### Configuration File

Start by creating a configuration file named `/src/lib/icon.config.json` with the following structure:

```json
{
  "config1": {
    "size": 40
  },
  "config2": {
    "size": 50
  }
}
```

In this JSON file, you can define different configurations (config1 and config2 in this case) for your icons, specifying attributes like size, variation, and color.

### Implementation

In your Svelte page file, make use of the configurations from the JSON file:

```html
<script lang="ts">
  type IconConfig = {
    config1: {
      size: number;
    };
    config2: {
      size: number;
    };
  };
  import config from '$lib/icon.config.json';
  import { Icon, A1F1f31f1f4, A1F344 } from 'svelte-twitter-emoji';

  const iconConfig: IconConfig = config;
  const config1 = iconConfig.config1;
  const config2 = iconConfig.config2;
</script>

<Icon {...config1} icon="{A1F1f31f1f4}" />
<Icon {...config2} icon="{A1F344}" />
```

We import the configurations from the JSON file and assign them to config1 and config2. We then utilize the Icon component with the spread attributes `{...config1}` and `{...config2}` to apply the respective configurations to each icon.

### Custom Default Icon

If you wish to create a custom default icon, you can follow these steps:

Create a Svelte component named `src/lib/MyIcon.svelte`:

```html
<script lang="ts">
  import type { ComponentType } from 'svelte';
  const config = {
    size: 30
  };
  import { Icon } from 'svelte-twitter-emoji';
  export let icon: ComponentType;
</script>

<Icon {...config} {icon} />
```

This component, `MyIcon.svelte`, accepts an `icon` prop which you can use to pass in the specific icon component you want to display. The default configuration is also applied to the icon.

### Implementation in a Page

To use your custom default icon in a Svelte page, do the following:

```html
<script>
  import MyIcon from '$lib/MyIcon.svelte';
  import { A1F1f31f1f4 } from 'svelte-twitter-emoji';
</script>

<MyIcon icon="{A1F1f31f1f4}" />
```

Here, we import the `MyIcon` component and the `A1F1f31f1f4` icon. By passing the `A1F1f31f1f4` icon to the `icon` prop of MyIcon, you apply the default configuration to the icon.

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

## Original source

[twitter/twemoji GitHub Repo](https://github.com/twitter/twemoji)

## License

[Svelte-Twitter-Emoji License](https://github.com/shinokada/svelte-twitter-emoji/blob/main/LICENSE)

[twitter/twemoji LICENSE](https://github.com/twitter/twemoji/blob/master/LICENSE)

## Other icons

[Svelte-Icon-Sets](https://svelte-svg-icons.codewithshin.com/)
