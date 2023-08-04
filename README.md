# Svelte Twitter Emoji

<div class="flex gap-2 my-8">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" alt="sponsor" height="25" style="height: 25px !important;"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-twitter-emoji" alt="npm" height="25" style="height: 25px !important;"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada" height="25" style="height: 25px !important;"></a>
<a href="https://creativecommons.org/licenses/by/4.0/" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-twitter-emoji" alt="License" height="25" style="height: 25px !important;"></a>
<a href="https://www.npmjs.com/package/svelte-twitter-emoji" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-twitter-emoji.svg" alt="npm" height="25" style="height: 25px !important;"></a>
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
pnpm i -D svelte-twitter-emoji
```

## Usages

In a svelte file:

```html
<script>
  import { Icon } from 'svelte-twitter-emoji';
</script>

<Icon name="1f43c" />
```

## Props

- @prop name;
- @prop width = replace_size;
- @prop height = replace_size;
- @prop role = 'img';
- @prop ariaLabel='icon name'

## IDE support

If you are using an LSP-compatible editor, such as VSCode, Atom, Sublime Text, or Neovim, hovering over a component name will display a documentation link, features, props, events, and an example.

## Size

Use the `width` and `height` props to change the size of icons.

```html
<Icon name="1f43c" width="100" height="100" />
```

If you are using Tailwind CSS, you can add a custom size using Tailwind CSS by including the desired classes in the class prop. For example:

```html
<Icon name="1f43c" class="shrink-0 h-20 w-20" />
```

## CSS frameworks suport

You can apply CSS framework color and other attributes directly to the icon component or its parent tag using the `class` prop.

Tailwind CSS example:

```html
<Icon name="1f43c" class="inline m-1" />
```

Bootstrap examples:

```html
<Icon name="1f43c" class="position-absolute top-0 px-1" />
```

## aria-label

All icons have aria-label. For example `1f43c` has `aria-label="1f43c"`.
Use `ariaLabel` prop to modify the `aria-label` value.

```html
<Icon name="1f43c" ariaLabel="panda icon" />
```

## Unfocusable icon

If you want to make an icon unfocusable, add `tabindex="-1"`.

```html
<Icon name="1f43c"  tabindex="-1" />
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
<Icon name="1f43c"  tabindex="0" />
```

## Using svelte:component

```html
<svelte:component this="{Icon}" name="1f43c" />
```

## Using onMount

```html
<script>
  import {Icon} from 'svelte-twitter-emoji';
  import { onMount } from 'svelte';
  const props = {
    name: '1f43c',
    size: '50',
  };
  onMount(() => {
    const icon = new Icon({ target: document.body, props });
  });
</script>
```


## Import all

Use `import {Icon, icons} from 'svelte-twitter-emoji';`.

```html
<script>
  import {Icon, icons} from 'svelte-twitter-emoji';
</script>

{#each Object.keys(icons) as name}
<div class="flex gap-4 items-center text-lg">
  <Icon name={name} class="shrink-0"/>
  {name}
</div>
{/each}
```

## Other icons

[Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)