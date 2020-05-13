<!--lint disable no-dead-urls-->
<!-- ignore all dead urls because of https://github.com/sindresorhus/awesome-lint/issues/89 -->

# Awesome Tailwind CSS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Lint Awesome List](https://github.com/aniftyco/awesome-tailwindcss/workflows/Lint%20Awesome%20List/badge.svg)

[<img src="tailwind-css-logo.svg" align="right" width="100">](https://tailwindcss.com)

> A curated list of awesome things related to Tailwind CSS

[Tailwind CSS](https://tailwindcss.com) is a utility-first CSS framework for rapidly building custom user interfaces.

---

🌟 **[Tailwind UI is hiring](https://jobs.tailwindui.com/full-stack-developer)** 🌟 - Help define and build the future of their developer tools and products.

---

## Contents

- [Plugins](#plugins)
- [UI Libraries & Components](#ui-libraries--components)
- [Resources](#resources)
  - [Useful Links](#useful-links)
  - [Tools](#tools)
  - [Starters, Templates & Themes](#starters-templates--themes)
  - [IDE Extensions](#ide-extensions)
  - [Open-Source Projects](#open-source-projects)
  - [Learning](#learning)
  - [Apps & Websites](#apps--websites)

## Plugins

- [Custom Forms (Official)](https://github.com/tailwindcss/custom-forms) - Adds better default styles to form elements.
- [Theming (Dark/Light)](https://github.com/hawezo/tailwindcss-theming) - Adds powerful theming capabilities with CSS variables and `prefers-color-scheme`.
- [Text Indent](https://github.com/hacknug/tailwindcss-text-indent) - Adds `text-indent` utilities.
- [Image Rendering](https://github.com/hacknug/tailwindcss-image-rendering) - Adds `image-rendering` utilities.
- [Filters](https://github.com/benface/tailwindcss-filters) - Adds `filter` utilities.
- [Spinner](https://github.com/aniftyco/tailwindcss-spinner) - Adds a spinner utility.
- [Elevation](https://github.com/jonaskay/tailwindcss-elevation) - Adds [Material UI `elevation`](https://material.io/design/environment/elevation.html) utilities.
- [Caret Color](https://github.com/naoray/tailwind-caret-color) - Adds `caret` color utilities.
- [Direction](https://github.com/RonMelkhior/tailwindcss-dir) - Adds `RTL` and `LTR` variants.
- [Touch](https://github.com/SteadfastCollective/tailwindcss-touch) - Adds `touch` variants.
- [Blend Mode](https://github.com/hacknug/tailwindcss-blend-mode) - Adds `blend-mode` utilities.
- [Colorize](https://github.com/philippbosch/tailwindcss-colorize) - Adds `filter` utilities.
- [Writing Mode](https://github.com/magicspon/tailwindcss-writing-mode) - Adds `writing-mode` utilities.
- [Responsive Embed](https://github.com/drdogbot7/tailwindcss-responsive-embed) - Adds a `responsive-embed` component.
- [Aspect Ratio](https://github.com/webdna/tailwindcss-aspect-ratio) - Adds `aspect-ratio` utilities.
- [Hyphens](https://github.com/philippbosch/tailwindcss-hyphens) - Adds `hyphens` utilities.
- [Border Gradients](https://github.com/cossssmin/tailwindcss-border-gradients) - Adds `border-image` gradient utilities.
- [RFS](https://github.com/aerni/tailwindcss-rfs) - Adds [`RFS`](https://github.com/twbs/rfs) utilities.
- [Font Variant Numeric](https://github.com/philippbosch/tailwindcss-font-variant-numeric) - Adds `font-variant-numeric` utilities.
- [Dark Mode](https://github.com/ChanceArthur/tailwindcss-dark-mode) - Adds `dark` variants based on the `prefers-color-scheme` media query.
- [Vue.js](https://github.com/opdavies/tailwindcss-vuejs) - Adds visibility classes that work with Vue.js's `v-cloak` directive.
- [List Reset](https://github.com/opdavies/tailwindcss-list-reset) - Re-adds the `list-reset` class that was removed prior to Tailwind CSS 1.0.
- [Fluid](https://github.com/bradlc/tailwindcss-fluid) - Adds fluid sizing utilities.
- [Flexbox Order](https://github.com/035media/tailwindcss-flexbox-order) - Extends `order` utilities.
- [benface's gradients](https://github.com/benface/tailwindcss-gradients) - Adds gradient utilities.
- [lorisleiva's gradients](https://github.com/lorisleiva/tailwindcss-plugins/tree/master/gradients) - Adds background gradient utilities.
- [Alpha](https://github.com/bradlc/tailwindcss-alpha) - Adds alpha color variants.
- [Bootstrap Tables](https://github.com/drehimself/tailwindcss-tables) - Adds table utilities based on Bootstrap's tables.
- [Typography](https://github.com/benface/tailwindcss-typography) - Adds typography utilities.
- [Card](https://github.com/NathanHeffley/tailwindcss-card) - Adds card components.
- [Triangle After](https://github.com/chrisrowe/tailwindcss-triangle-after) - Adds CSS triangles utilities.
- [Scrims](https://github.com/brettgullan/tailwindcss-scrims) - Adds scrims utilities.
- [Colors to CSS Variables](https://github.com/n1kk/tailwind-color-vars) - Exports color configuration to CSS Custom Properties.
- [CSS Variables](https://github.com/omarkhatibco/tailwind-css-variables) - Exports configuration to CSS Custom Properties.
- [Spaced Items](https://github.com/n1kk/tailwindcss-spaced-items) - Adds `spaced` components that add fixed margins to all container items, except the last one.
- [Heropatterns](https://github.com/AndreaMinato/tailwind-heropatterns) - Adds [Hero Patterns](https://www.heropatterns.com) components.
- [Localized](https://github.com/hdodov/tailwindcss-localized) - Adds variants based on the HTML `lang` attribute, to use utilities only with certain languages.
- [Skip link](https://github.com/opdavies/tailwindcss-skip-link) - Adds a _Skip to main content_ accessible component.
- [Pseudo](https://github.com/Log1x/tailwindcss-pseudo) - Adds custom variants to Tailwind CSS's configuration.
- [Custom Native](https://github.com/SirNavith/tailwindcss-custom-native) - Leverages Tailwind CSS's configuration to allow the creation of utilities.
- [Truncate Multiline](https://github.com/jhta/tailwindcss-truncate-multiline) - Adds utilities to truncate multi-line text elements.
- [Debug Screens](https://github.com/jorenvanhee/tailwindcss-debug-screens) - Adds a component that shows the currently active screen (responsive breakpoint).
- [Dark Mode with Class](https://github.com/danestves/tailwindcss-darkmode) - Adds `dark` variants based on CSS classes.
- [CSS Logical Properties](https://github.com/omarkhatibco/tailwind-css-logical-properties) - Generate classnames for CSS Logical Properties for margin, padding, border-width, border-raduis, text-align, float & writing-mode.
- [CSS Scroll Snap](https://github.com/hawezo/tailwindcss-scroll-snap) - Adds `scroll-snap` utilities.
- [Shadow Outline Colors](https://github.com/octoper/tailwindcss-shadow-outline-colors) - Adds `box-shadow` utilities based on configured colors.
- [Tooltip Arrows After](https://github.com/gvital3230/tailwindcss-tooltip-arrow-after) - Adds CSS utilities for tooltip arrows with configurable border and background.
- [Bidirectional](https://github.com/20lives/tailwindcss-rtl) - Adds utilities for creating multilingual bidirectional layouts.

> 🛑 - _The functionalities these plugins below offer have been fully or partially implemented in the latest Tailwind CSS versions._

- 🛑 [Visually Hidden](https://github.com/webdna/tailwindcss-visuallyhidden) - Adds screen reader utilities.
- 🛑 [Object Fit](https://github.com/hendrikeng/tailwindcss-object-fit) - Adds `object-fit` utilities.
- 🛑 [Object Position](https://github.com/hacknug/tailwindcss-object-position) - Adds `object-position` utilities.
- 🛑 [Accessibility](https://github.com/jack-pallot/tailwindcss-accessibility) - Adds screen reader utilities.
- 🛑 [Layout](https://github.com/benface/tailwindcss-layout) - Adds some layout utilities.
- 🛑 [Important](https://github.com/chasegiunta/tailwindcss-important) - Adds an `important` variant.
- 🛑 [Grid](https://github.com/chrisrowe/tailwindcss-grid) - Adds CSS grids utilities.
- 🛑 [Transforms](https://github.com/benface/tailwindcss-transforms) - Adds `transform` utilities.
- 🛑 [benface's transitions](https://github.com/benface/tailwindcss-transitions) - Adds configurable transition utilities, with or without CSS variables.
- 🛑 [webdna's transitions](https://github.com/webdna/tailwindcss-transition) - Adds configurable transition utilities.
- 🛑 [glhd's transitions](https://github.com/glhd/tailwindcss-plugins) - Adds basic transition utilities.
- 🛑 [Cursor Extended](https://github.com/hacknug/tailwindcss-cursor-extended) - Extends `cursor` utilities.
- 🛑 [CSS Alpha Colors](https://github.com/soueuls/tailwind-color-alpha) - Adds opacity variants to existing colors.

## UI Libraries & Components

- [tails-ui](https://github.com/knipferrc/tails-ui) - React UI library using Tailwind CSS.
- [VueTailwind](https://github.com/alfonsobries/vue-tailwind) - Vue.js UI library using Tailwind CSS.
- [Tailwind Toolbox](https://www.tailwindtoolbox.com) - Tailwind CSS templates, components and resources.
- [Tailwind Templates](https://www.tailwindtemplates.io) - Tailwind CSS components.
- [jQuery + Tailwind Checkbox Toggle](https://craigerskine.github.io/jquery-tailwind-checkbox-toggle) - Switches using jQuery and Tailwind CSS.
- [Tailwind Starter Kit](https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/presentation?ref=awesome-tailwindcss) - Tailwind Starter Kit is an extension for Tailwind CSS, Free and Open Source.
- [a17t](https://a17t.miles.land) - Atomic design toolkit built to extend Tailwind CSS.
- [Tailwind Blocks](https://mert.dev/tailwind-blocks) - Tailwind CSS UI blocks for landing pages.
- [Meraki UI Components](https://merakiui.com) - Beautiful Tailwind CSS components that support RTL languages.

## Resources

### Useful Links

- [Tailwind CSS website](https://tailwindcss.com) - Official Tailwind CSS website.
- [Tailwind CSS on GitHub](https://github.com/tailwindcss/tailwindcss) - Official Tailwind CSS repository.
- 🌟 [Tailwind UI](https://tailwindui.com) 🌟 - Component library made with Tailwind CSS.
- [Discussion Repository](https://github.com/tailwindcss/discuss) - Official Tailwind CSS repository for discussions.
- [Tailwind Components](https://tailwindcomponents.com) - Community-driven Tailwind CSS component repository.
- [Built With Tailwind](https://builtwithtailwind.com/) - Community-driven collection of awesome websites built with Tailwind CSS.
- [Tailwind Cheat Sheet](https://umeshmk.github.io/Tailwindcss-cheatsheet) - Tailwind CSS class names, variants and directives cheat sheet.
- [Tailwind Cheat Sheet](http://nerdcave.com/tailwind-cheat-sheet) - Tailwind CSS class names cheat sheet.
- [Tailwind Cheat Sheet](https://github.com/LeCoupa/awesome-cheatsheets/blob/master/frontend/tailwind.css) - Tailwind CSS class names in one single file.
- [tailwind.run](https://tailwind.run) - Tailwind CSS fiddle with built-time features (online).
- [Maizzle](https://maizzle.com/) - Framework for rapid email prototyping with Tailwind CSS.

### Tools

**Legend**: 🌍 Online accessible · 🧪 Conversion or upgrade tool · 🔧 Generator · 🅰 Typing/enforcement · 💼 Plugins/Tools/Extensions for external services

- 🌍🔧 [Color shades generator](https://javisperez.github.io/tailwindcolorshades) - Color shades generator for Tailwind CSS (online).
- 🌍🔧 [Color palette generator](https://adevade.github.io/color-scheme-generator) - Color palette generator that outputs a color configuration for Tailwind CSS (online).
- 🌍 [Tailwind Button Playground](https://minthemiddle.github.io/tailwind-button-playground) - Playground for theming a button with Tailwind CSS (online).
- 🌍🔧 [Stitches](https://stitches.hyperyolo.com/) - Template generator with Tailwind (online).
- 🌍🔧 [Tailwind Colors](https://tailwind-colors.meidev.co) - Color configuration generator for Tailwind CSS.
- 🌍🧪 [Tailwind Automatic Prefix Applicator](https://github.vue.tailwind-prefix.cbass.dev) - Tailwind classes' prefixer tool.
- 🧪 [Tailwindo](https://github.com/awssat/tailwindo) - Bootstrap to Tailwind CSS converter.
- 🧪 [Tailupgrade](https://github.com/virkillz/tailupgrade) - Conversion tool for upgrading HTML files from Tailwind CSS v0.x to v1.0.
- 🧪 [Tailwind Shift](https://github.com/awssat/tailwind-shift) - Upgrade tool for upgrading from Tailwind CSS v0.7 to v1.0.
- 🌍 [tailwind.run](https://tailwind.run) - Tailwind CSS fiddle with built-time features (online).
- 🅰 [typed-tailwind](https://github.com/dvkndn/typed-tailwind) - TypeScript typings for Tailwind CSS.
- 💼🔧 [Zeplin Config & Class generator](https://extensions.zeplin.io/5ae2d20017c57fd249c9876f) - Zeplin extension that generates Tailwind configurations.
- 💼 [Gatsby Plugin Tailwind CSS](https://github.com/muhajirframe/gatsby-plugin-tailwindcss) - Gastby plugin to use Tailwind CSS with CSS-in-JS.
- 💼 [Gridsome Plugin Tailwind CSS](https://github.com/brandonpittman/gridsome-plugin-tailwindcss) - Gridsome plugin to use Tailwind CSS with PurgeCSS, postcss-import, and postcss-env.
- 🔧 [re-tailwind](https://github.com/phthhieu/re-tailwind) - ReasonML utility that generates Tailwind classes.
- 🅰 [react-native-tailwindcss](https://github.com/TVke/react-native-tailwindcss) - React Native typing system.
- 💼 [Alfred Workflow](https://github.com/clnt/alfred-tailwindcss-docs) - Fast Tailwind CSS documentation search application.
- 💼 [ng-tailwindcss](https://github.com/tehpsalmist/ng-tailwindcss) - CLI tool for integrating Tailwind CSS into Angular-CLI projects.
- 💼 [vue-cli-plugin-tailwind](https://github.com/forsartis/vue-cli-plugin-tailwind) - Vue CLI plugin that adds Tailwind CSS to a project.
- 💼 [Tailwind CSS Figma Kit](https://github.com/impulse/tailwindcss-figma-kit) - Figma Kit for Tailwind CSS.
- 💼 [Tailwind CSS Figma Plugin](https://github.com/impulse/tailwindcss-figma-plugin) - Figma plugin that integrates Tailwind CSS.
- 🧪 [RustyWind](https://github.com/avencera/rustywind) - CLI tool for sorting Tailwind CSS classes.
- 🔧 [Protoship Codegen](https://protoship.io) - Code generator that creates Tailwind CSS based HTML & CSS from Sketch designs.
- 💼 [@nuxtjs/tailwindcss](https://github.com/nuxt-community/tailwindcss-module) - Tailwind CSS module for NuxtJS with PurgeCSS and modern CSS (preset env 1).
- 💼 [preact-cli-tailwind](https://github.com/agneym/preact-cli-tailwind) - Adds Tailwind CSS module as PostCSS plugin and sets up PurgeCSS in production for PreactJS CLI Projects.
- 💼🔧 [@tailwindcssinjs/macro](https://github.com/Arthie/tailwindcssinjs) - Babel macro that transforms Tailwind CSS classes into objects for CSS-in-JS libraries.
- 💼🔧 [twin.macro](https://github.com/ben-rogerson/twin.macro) - Use Tailwind classes within any CSS-in-JS library.

### Starters, Templates & Themes

**Legend**: 🔧 Starters & Boilerplates · 🛠 Starter packages · 🎨 Templates & Themes

- 🔧 [Jekyll Starter](https://github.com/mhanberg/jekyll-tailwind-starter) - Jekyll starter using Tailwind CSS.
- 🔧 [Jekyll Starter](https://github.com/taylorbryant/tailwind-jekyll) - Jekyll starter using Tailwind CSS.
- 🔧 [Gulp Starter](https://github.com/simonswiss/tailwind-starter) - Gulp starter using Tailwind CSS.
- 🔧 [Gatsby Starter](https://github.com/taylorbryant/gatsby-starter-tailwind) - Gatsby starter using Tailwind CSS.
- 🔧 [Gatsby Starter + TypeScript](https://github.com/impulse/gatsby-typescript-tailwind) - Gatsby starter using Tailwind CSS and TypeScript.
- 🔧 [Gatsby Starter + Emotion JS](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter) - Gatsby starter using Tailwind CSS and Emotion JS.
- 🔧 [Create React App Boilerplate with EmotionJS](https://github.com/muhajirframe/react-tailwind-emotion-starter) - CRA boilerplate using Tailwind CSS and Emotion JS.
- 🔧 [Create React App Boilerplate](https://github.com/kriswep/cra-tailwindcss) - CRA boilerplate using Tailwind CSS.
- 🔧🛠 [Create React App script with PurgeCSS](https://github.com/DemianD/create-react-app-tailwindcss) - CRA script that adds Tailwind CSS and PurgeCSS.
- 🔧 [Dogpatch](https://github.com/jack-pallot/dogpatch) - WordPress starter using Webpack, Vue, Babel and Tailwind CSS.
- 🔧 [Next.js Starter](https://github.com/oddstronaut/tailwind-next) - Next.js boilerplate using Tailwind CSS.
- 🔧 [Sapper & Svelte Starter](https://github.com/EricPKerr/sapper-tailwindcss-starter) - Svelte boilerplate using Sapper, Tailwind CSS, Purge CSS, Prettier and ESLint.
- 🔧 [Netlify Lambda Static Starter](https://github.com/HugoDF/netlify-lambda-tailwind-static-starter) - Netlify Lambda boilerplate using Tailwind CSS.
- 🔧 [Ruby on Rails Example Project](https://github.com/jvanbaarsen/tailwindcss-rails-example) - Rails example application using Tailwind CSS.
- 🔧🛠 [Laravel Frontend Preset](https://github.com/laravel-frontend-presets/tailwindcss) - Front-end preset using Tailwind CSS for the Laravel Framework.
- 🔧🛠 [Laravel Dark Frontend Preset](https://github.com/Naoray/dark-tailwind-preset) - Dark-themed front-end preset using Tailwind CSS for the Laravel Framework.
- 🔧 [Laravel Boilerplate](https://github.com/hawezo/laravel-boilerplate) - Laravel boilerplate using Tailwind CSS, Inertia JS, TypeScript, Vue, and font-end theming.
- 🔧 [Hugo Theme Starter with Tailwind CSS](https://github.com/dirkolbrich/hugo-theme-tailwindcss-starter) - Hugo theme starter using Tailwind CSS.
- 🔧 [Eleventy Web Starter](https://github.com/scottishstoater/jamstack-web-starter) - Starter kit using Eleventy, Tailwind CSS, Webpack and PostCSS.
- 🔧 [Nanoc Starter](https://github.com/arkency/nanoc-parcel-tailwind-starter) - Nanoc starter using Tailwind CSS.
- 🎨 [Gatsby Serif](https://github.com/windedge/gatsby-tailwind-serif) - Gatsby's serif theme using Tailwind CSS.
- 🎨 [Tailwind Admin](https://github.com/tailwindadmin/admin) - Administration panel template with Tailwind CSS.
- 🎨 [Wordpress Tailwind CSS + Google PWA](https://github.com/ri7nz/Mesjid) - Wordpress Theme and PWA using Tailwind CSS.
- 🎨 [Seminyak Hugo Theme](https://git.habd.as/jhabdas/seminyak) - Hugo Theme using Tailwind CSS.
- 🎨 [Create React App Template with Tailwind CSS + TypeScript](https://github.com/dance2die/cra-template-tailwindcss-typescript) - CRA Template to  add Tailwind CSS + TypeScript support.

### IDE Extensions

- [Tailwind CSS IntelliSense for VS Code](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - Visual Studio Code IntelliSense extension for Tailwind CSS.
- [Tailwind CSS Styled Snippets for VS Code](https://marketplace.visualstudio.com/items?itemName=muhajirframe.tailwind-styled-snippets) - Visual Studio Code snippet extension for Tailwind CSS.
- [Tailwind CSS IntelliSense for Neovim](https://github.com/iamcco/coc-tailwindcss) - Neovim IntelliSense extension for Tailwind CSS.
- [Headwind for VS Code](https://github.com/heybourn/headwind) - Visual Studio Code class sorter for Tailwind CSS.

### Open-Source Projects

- [Goodwork](https://github.com/iluminar/goodwork) - Project Management & Collaboration tool.
- [Statusfy](https://github.com/bazzite/statusfy) - Status page system using Tailwind CSS.
- [Todolist](https://github.com/guillaumebriday/todolist-frontend-vuejs) - To-do list application using Tailwind CSS.
- [LeagueStats](https://github.com/vkaelin/LeagueStats) - Statistics website for League of Legends players.
- [SapperCommerce](https://github.com/itswadesh/sapper-ecommerce) - E-commerce storefront using Svelte & Tailwind CSS.
- [Misiki Books](https://github.com/itswadesh/misiki-books) - Book shop using Vue + Moltin + Tailwind CSS.

### Learning

**Legend**: 🧪 Sample · 🔧 Setup Tutorial · 🎬 Video Tutorial · 🎓 Component or Page Tutorial · 🎥 Cast

- 🧪 [Tailwind Dark Mode Theme Switcher](https://github.com/huphtur/tailwind-theme-switcher) - Switching themes with CSS Custom Properties and Tailwind CSS.
- 🧪 [Plugin Examples (Official)](https://github.com/tailwindcss/plugin-examples) - Official plugin examples.
- 🧪 [Acquia](https://github.com/opdavies/rebuilding-acquia) - Acquia's hosting dashboard rebuilt with Vue.js and Tailwind CSS.
- 🧪 [Navbar](https://codepen.io/joshmanders/pen/PQQBoR) - Navbar made with Vue.js and Tailwind CSS.
- 🧪 [Toggle switch](https://github.com/TowelSoftware/tailwindcss-toggle) - Switch using Tailwind CSS.
- 🔧 [Testing Tailwind CSS plugins with Jest](https://www.oliverdavies.uk/articles/testing-tailwindcss-plugins-with-jest) - How to test Tailwind CSS plugins with Jest.
- 🔧 [Tailwind CSS with Webpack 4 and PostCSS](https://paramagicdev.github.io/my-blog/javascript/tailwindWebpackPostCSS) - How to setup Tailwind CSS with PostCSS and Webpack.
- 🔧 [Tailwind CSS with CSS-in-JS](https://medium.com/@AndrewDelPrete/using-tailwindcss-with-css-in-js-32ae6796f95c) - How to use Tailwind CSS with CSS-in-JS.
- 🔧 [Tailwind CSS in a Laravel Project](https://nick-basile.com/blog/post/setting-up-tailwind-in-a-laravel-project) - How to setup Tailwind CSS in a Laravel project.
- 🔧 [Tailwind CSS with Ember](https://eaf4.com/how-to-add-tailwindcss-to-an-ember-app) - How to add Tailwind CSS to an Ember application.
- 🔧 [Sage WordPress theme and Tailwind CSS](https://roots.io/guides/how-to-setup-tailwind-css-in-sage) - How to setup Tailwind CSS in Sage.
- 🔧 [Tailwind CSS with GatsbyJS](https://dev.to/jakedohm_34/using-tailwind-with-gatsby-js-10fj) - How to use Tailwind CSS with Gatsby.
- 🔧 [Tailwind CSS with Phoenix 1.4](https://equimper.com/blog/how-to-setup-tailwindcss-in-phoenix-1.4) - How to setup Tailwind CSS in Phoenix 1.4.
- 🔧 [Extend Tailwind CSS](https://web-crunch.com/how-to-extend-tailwind-css) - How to Extend Tailwind CSS.
- 🎬 [Rebuilding Laravel.io](https://www.youtube.com/watch?v=ZrRRMBaz5Z0) - Rebuilding Laravel.io with Tailwind CSS.
- 🎬 [Rebuilding Coinbase](https://www.youtube.com/watch?v=7gX_ApBeSpQ) - Rebuilding Coinbase with Tailwind CSS.
  - [Codepen](https://codepen.io/adamwathan/pen/RxWrZr)
- 🎬 [Rebuilding Twitter](https://www.youtube.com/watch?v=Pg_5Ni1_bg4) - Rebuilding Twitter with Tailwind CSS.
  - [CodePen](https://codepen.io/drehimself/full/vpeVMx)
- 🎬 [Rebuilding YouTube](https://www.youtube.com/watch?v=qxQKnqmNKv0) - Rebuilding YouTube with Tailwind CSS.
- 🎬 [Rebuilding Netlify](https://www.youtube.com/watch?v=_JhTaENzfZQ&t=1263s) - Rebuilding Netlify with Tailwind CSS.
- 🎬 [Rebuilding Resolute](https://www.youtube.com/watch?v=banq3TfAPYk) - Rebuilding Resolute with Tailwind CSS.
- 🎬 [Let's Build: Movie Production Landing Page](https://web-crunch.com/tailwind-css-movie-production-landing-page) - Building a movie production landing page with Tailwind CSS.
- 🎬 [Lets Build: Responsive Navbar](https://web-crunch.com/lets-build-tailwind-css-responsive-navbar) - Building a responsive navbar with Tailwind CSS.
- 🎬 [Let's Build: Dribbble Shot](https://web-crunch.com/lets-build-tailwind-css-dribbble-shot) - Dribbble shot with Tailwind CSS.
- 🎬 [Let's Build: Tweet component](https://web-crunch.com/lets-build-tailwind-css-tweet) - Building a Tweet component with Tailwind CSS.
- 🎓 [Modal Dialog](https://codeburst.io/creating-a-modal-dialog-with-tailwind-css-42722c9aea4f) - Creating a modal dialog with Tailwind CSS.
- 🎓 [Building real-world UIs using Tailwind CSS](https://github.com/asvny/building-realworld-user-interfaces-using-tailwind) - Examples of building UIs of Shopify, Spotify, Netlify and Atlassian using Tailwind CSS.
- 🎓 [Rebuilding FreshBooks](http://joey.io/rebuilding-freshbooks-with-tailwind-css) - Rebuilding FreshBooks with Tailwind CSS.
- 🎓 [Login Page (PingPing)](https://stefanbauer.me/building-pingping/we-build-a-login-using-tailwindcss) - Creating a login page with Tailwind CSS.
- 🎓 [Login Page](https://mustafaaloko.github.io/2017/tailwind-css-building-a-login-page) - Creating a login page with Tailwind CSS.
- 🎓 [Vue.js Component with Tailwind and Laravel](https://nick-basile.com/blog/post/how-to-build-a-vuejs-component-with-tailwind-in-a-laravel-project) - Building a Vue.js component with Tailwind CSS in a Laravel project.
- 🎓 [Vue.js Modal](https://nick-basile.com/blog/post/build-a-customizable-vuejs-modal-with-tailwind-css) - Building a customizable modal with Tailwind CSS and Vue.js.
- 🎓 [Navigation](https://nick-basile.com/blog/post/building-a-nav-with-tailwind-css) - Building a navigation with Tailwind CSS.
- 🎓 [Forms with Tailwind CSS](https://css-tricks.com/style-form-tailwind-css) - How to style a form with Tailwind CSS.
- 🎓 [Photo gallery with CSS grids](https://nick-basile.com/blog/post/building-a-photo-gallery-with-css-grid-and-tailwind-css) - Building a photo gallery with CSS grids and Tailwind CSS.
- 🎓 [Rebuilding Bartik](https://www.oliverdavies.uk/articles/rebuilding-bartik-with-vuejs-tailwind-css) - Rebuilding Bartik (Drupal's default theme) with Vue.js and Tailwind CSS.
- 🎓 [Rebuilding Airbnb's Home Page](https://web-crunch.com/re-create-airbnbs-home-page-with-tailwind-css) - Rebuilding Airbnb's Home Page with Tailwind CSS.
- 🎥 [Laracasts Weekly Stream: Tailwind](https://www.youtube.com/watch?v=HIPgzWS-Bxg)
- 🎥 [More experimentation with Tailwind CSS](https://www.youtube.com/watch?v=nBzfVK3QUzM)
- 🎥 [Rebuilding Spotify](https://youtu.be/SLGb2RLie9w)
- 🎥 [Rebuilding Discord](https://youtu.be/t54tuaoHVLo)
- 🎥 [Rebuilding Meetup](https://youtu.be/ULe6yKJrFuI)

### Apps & Websites

- [Josh Manders](https://joshmanders.com)
- [Audience](https://startaudience.com)
- [Matt Stauffer](https://mattstauffer.com)
- [Miguel Piedrafita](https://miguelpiedrafita.com)
- [Blogcast](https://blogcast.host)
- [Lichter.io (Alexander Lichter)](https://lichter.io)
- [Rias](https://rias.be)
- [Freek Van der Herten](https://murze.be)
- [Taylor Bryant](https://taylorbryant.blog)
- [Oliver Davies](https://www.oliverdavies.uk)
- [BaseCode](https://basecodefieldguide.com)
- [University of West London](https://www.uwl.ac.uk)
- [Joey Beninghove](https://joey.io)
- [Stefan Bauer](https://stefanbauer.me)
- [Laravel Spark](https://spark.laravel.com)
- [Sitesauce](https://sitesauce.app)
- [Milan Chheda](https://milanchheda.com)
- [Matheus Lima](https://matheuslima.com.br)
- [CSS Cursors](https://css-cursors.netlify.com)
- [Developmint](https://developmint.de)
- [Rational Investment Management](https://rationalim.com)
- [Stephen Popoola](https://stephenpopoola.uk)
- [Vince Mitchell](http://vincemitchell.me)
- [Marco Mark](https://www.marcomark.net)
- [Nehal Hasnayeen](https://hasnayeen.github.io)
- [Plowman Craven](https://www.plowmancraven.co.uk)
- [Our Name is Mud](https://www.ournameismud.co.uk)
- [BudgetDuo](https://budgetduo.com)
- [Quickwords](https://quickwords.co)
- [The MBR Site](https://www.thembrsite.com)
- [Peter Fox](https://www.peterfox.me)
- [Martin Williams](https://www.martinwilliamsart.co.uk)
- [Brahms Electric Hearses](https://www.electrichearse.co.uk)
- [Sjabloon](https://www.getsjabloon.com)
- [Guillaume Briday](https://guillaumebriday.fr)
- [Hello Sun](https://hellosun.brussels)
- [OpenEmu](http://openemu.org)
- [sleeplessmind.info](https://sleeplessmind.info)
- [The Speedcube Site](https://speedcube.site)
- [Woburn Mosaic](https://www.woburnmosaic.co.uk)
- [Hunsbury Hot Tubs](https://www.hunsburyhottubs.co.uk)
- [DigitalDam](https://digitaldam.ca)
- [SlidesGo](https://slidesgo.com)
- [BuildPulse](https://buildpulse.io)
- [ScrumGenius](https://scrumgenius.com)
- [AwesomeTechStack](https://awesometechstack.com)
- [Allan White](https://allanwhite.design/)
- [Dance of Dawn](https://www.danceofdawn.com/)
- [MOODZ Travel Gallery](https://moodz.yakovleva.dev/)
- [Laravel Livewire](https://laravel-livewire.com/)
- [Valohai](https://valohai.com)
- [GitInLog](https://www.gitinlog.com/)
- [UptimeMate](https://uptimemate.com/)
- [myDID](https://mydid.dev)
- [Home Away From Home](https://homeawayfromhome.online)
- [Litekart](https://www.litekart.in)
- [NuxtJS Documentation](https://nuxtjs.org)
- [Vaggelis Yfantis](https://octoper.me)
- [This Month Rocks](https://thismonth.rocks)
- [Aditya Agarwal](https://devadi.netlify.com)
- [Dumpsters.com](https://www.dumpsters.com)
- [Rasul Kireev](https://rasulkireev.com)
- [Built with Django](https://builtwithdjango.com)
- [Log1x](https://log1x.com)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [NiftyCo](https://aniftyco.com) has waived all copyright and related or neighboring rights to this work.
