# Contributing guide

After your pull request, this list must still be [Awesome](https://github.com/sindresorhus/awesome)-elligible.

## General guidelines

1. The formats and categories described below must be respected.
2. The added item must be **awesome**. It means, really good and useful. If you have doubts about its awesomess, it probably isn't... sorry.
   - > Only has awesome items. Awesome lists are curations of the best, not everything. _— [Awesome Guidelines](https://github.com/sindresorhus/awesome/blob/master/pull_request_template.md#requirements-for-your-awesome-list)_
3. Unless specified otherwise below, an item must be added to the bottom of its emoji group.
4. Your project must not violate the [Tailwind brand usage guidelines](https://tailwindcss.com/brand#usage).

## Formats, naming conventions and descriptions

- Every item must have the following format: `[Item name](link) - Description.`.
- If a category has an emoji that applies to a new item, it must be used.
- Every name and description must be in English.
- Every mention to Tailwind CSS must use the exact name `Tailwind CSS`, except for plugin/library/product names.
  - ✖ `TailwindCSS`
  - ✖ `tailwind CSS`
  - ✖ `Tailwind`
- Descriptions must not start with "The", "A" or similar.
  - ✔ Component library made with Tailwind CSS.
  - ✖ A plugin that adds variants for dark mode.
  - ✖ A tool for upgrading Tailwind CSS.
- Descriptions must start with an uppercase character and ends with a period.
- Descriptions must be **short** and **explicit**.
  - ✔ Adds better default styles to form elements.
  - ✔ Adds configurable transition utilities, with or without CSS variables.
  - ✖ Adds classes for showing and hiding elements in different display variations in combination with Vue's v-cloak directive. - **Too long**
  - ✖ Adds utility classes - **Not explicit**
- [Plugins](README.md/#plugins) descriptions must start with a verb.
  - ✔ Adds `object-position` utilities.
  - ✔ Extends `object-position` utilities.
  - ✖ A plugin that adds variants for dark mode.
  - ✖ Additional variants for touch based media queries.
- Descriptions must describe the resource, not be a slogan.
  - ✔ Visual Studio Code IntelliSense extension for Tailwind CSS.
  - ✔ React UI library using Tailwind CSS.
  - ✖ Brings Tailwind CSS into React.

# Categories

## Useful links

This category contains resources that are official _or_ widely known and used in the Tailwind CSS community. If you find something that we forgot to add here, or if you built something a while ago that has become quite popular in the community, feel free to add it. Otherwise, it most likely belongs in the other categories.

## IDE extensions

If you made an extension that makes the usage of Tailwind CSS easier, make sure it is properly distributable before adding it to the list. Please use the format `[<extension type/functionality> for <IDE name>](link) - <Extension functionality> for <Full IDE name>` when applicable.

## Plugins

This category must only contain Tailwind CSS plugins that use the [official plugin architecture](https://tailwindcss.com/docs/adding-custom-styles) to extend the framework. New plugins must be added to the bottom of the corresponding category, represented by emojis.

## Tools

Tools can be anything that help with setting up or working with Tailwind CSS, or stuff that extend other services to bring Tailwind CSS in them.

## UI libraries, components & templates

This category must contain UI libraries made for Tailwind CSS, standalone components that are optimized for distribution, and full, standalone templates.

# Pull request and commits

You can name your pull request and commits however you want, but for clarity, [conventional commits](http://conventionalcommits.org/) are welcome. Pull request will be squashed upon merge.

Here are the keywords used in this list:

- `add` — For adding a resource to the list. - eg. `add(adapters): Vue.js adapter`
- `remove` — For removing a resource to the list. - eg. `remove(item-name): outdated resource`
- `update` — For updating a resource to the list. - eg. `update(item-name): fix typographical error in description`
- `chore` — For anything else.
