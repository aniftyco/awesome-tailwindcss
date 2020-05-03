# Contributing Guide

Please be sure to follow the [Tailwind CSS Community Guidelines](https://github.com/tailwindcss/tailwindcss/blob/master/.github/CODE_OF_CONDUCT.md). After your pull request, this list must still be elligible for [awesome](https://github.com/sindresorhus/awesome).

## General Guidelines

1. Respect the formats and categories described below.
2. Make sure your item is **awesome**.
    - > Only has awesome items. Awesome lists are curations of the best, not everything. 
      > *— [Awesome Guidelines](https://github.com/sindresorhus/awesome/blob/master/pull_request_template.md#requirements-for-your-awesome-list)*
3. If the item is a [plugin](README.md/#plugins), an [UI Library/Component](README.md/#ui-libraries--components), an [open-source project](README.md/#open-source-projects), or an [app or website](README.md/#apps--websites), it must be added **to the bottom of the list**. The other [Resources](README.md/#resources) sub-categories may have specific rules described in their sections.
4. Use [`awesome-lint`](https://github.com/sindresorhus/awesome-lint) before sending your pull request. You can ignore the following lint errors:
    - `License was not detected by GitHub` (`remark-lint:awesome/github`)
    - `The repository should have ... as a GitHub topic` (`remark-lint:awesome/github`)
    - `Link to ... is dead` (`remark-lint:no-dead-urls`) (until https://github.com/transitive-bullshit/check-links/issues/4 is resolved)
5. Please list the items you have added in the description of the pull request (if applicable) for faster PR approbation.
6. Be awesome. 👓

## Formats, Naming Conventions and Descriptions

- Every item MUST have the following format: `[Item Name](link) - Description.`.
- Every name and description must be in english.
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
- Descriptions must describe the resource, not be a slogan. This rule applies to every resource sub-category except [Demos, Samples & Tutorials](README.md/#demos-samples--tutorials).
    - ✔ Visual Studio Code IntelliSense extension for Tailwind CSS.
    - ✔ React UI library using Tailwind CSS.
    - ✖ Brings Tailwind CSS into React.
- [Demos, Samples & Tutorials](README.md/#demos-samples--tutorials) descriptions must be a short but explicit description of the content. It *should* start with a verb or by "How to" when applicable.
    - ✔ Rebuilding Acquia’s hosting dashboard with Vue.js and Tailwind CSS.
    - ✖ Acquia’s hosting dashboard rebuilt with Vue.js and Tailwind CSS.
    - ✔ How to setup Tailwind CSS in Phoenix 1.4.
    - ✖ Setting up Tailwind CSS in Phoenix 1.4

# Categories

## Plugins

This category must only contain Tailwind CSS plugins that use the [official plugin architecture](https://tailwindcss.com/docs/plugins/) to extend the framework. When adding your plugin to the list, **to the bottom**, but **ABOVE the deprecated plugins**.

## UI Libraries & Components

This category should contain UI libraries made with and for Tailwind CSS, as well as standalone components that are optimized for distribution. Components examples that are not distributable with a package manager should be in [Demos, Samples & Tutorials](README.md/#demos-samples--tutorials). When adding your item to the list, please add it **to the bottom**.

## Resources

Resources are stuff that are made with, for, or are useful for Tailwind CSS. If Tailwind CSS is not the main focus of the resource, maybe it doesn't belong to this list.

### Useful Links

This category contains resources that are official *or* widely known and used in the Tailwind CSS community. If you find something that we forgot to add here, or if you built something a while ago that has become quite popular in the community, feel free to add it. Otherwise, it most likely belongs in the other categories.

### Tools

Tools can be things that help with setting up or working with Tailwind CSS, or stuff that extend other services to bring Tailwind CSS in them. The category has tags in the form of emojis. If you find no emoji corresponding to your tool but you believe there should be one, feel free to *propose* to add one in your pull request. If there are multiple amojis that correspond to your item, you can stack them.

### Starters, Templates & Themes

This category contains boilerplates projects, starters projects and tools made for using Tailwind CSS as well as themes made with or for Tailwind CSS. When adding an item to this list, try to logically group it next to similar items. You can also stack emojis if you think it is needed.

### IDE Extensions

If you made an extension that makes the usage of Tailwind CSS easier, make sure it is properly distributable before adding it to the list. Please use the format `[<extension type/functionality> for <IDE name>](link) - <Full IDE name> <extension functionality> for Tailwind CSS` when applicable.

### Open-Source Projects

Open-source projects that use Tailwind CSS can be featured in this category if you feel that it is awesome enough. Please don't add newly-created projects though, and wait for them to get sort of popular before sending your pull request. The item must be added at the end of the list.

### Learning

Anything that is a material that can be used to better understand Tailwind CSS can be added here. Awesome blog posts, code samples, tutorials on any platform are welcome. When adding an item, please try to logically group them below other similar items, or by emoji.

### Apps & Websites

Any application, blog, or website that was built with Tailwind CSS and that is awesome enough can be added here. It must be something that features what can be done with the framework. You can promote your own stuff here, but it should be awesome enough, as it can't be a list of all Tailwind CSS websites ever. No description needed.
