# vue-tailwindcss



# Installation Tailwindcss in Vue/Vite
[Doc](https://tailwindcss.com/docs/guides/vite#vue)

# Content
 - Utility classes
## Colors
 - [Doc](https://tailwindcss.com/docs/customizing-colors)
## Customization
 - Should add property in extend object, not in theme, because it will override tailwindcss class
 - Configuration
 - Content
 - Theme
 - Screens
 - Colors
 - Spacing
 - Plugins
 - Preset

## Typography
 - font...
 - text...
 - whitespace
 - word break
 - content (`after:content-['_↗'] `)
 ...
## Spacing & Sizing
 - Space:
  * Padding
  * Margin
  * Space Between
 - Sizing:
  * Width
  * Min-Width
  * Height
  * Min-Height
  * Size
  ...

## Flex
 - Flex, shrink, grow,...
 - Gap
 - Justify Content,...

## Grids
 - grid, grid-cols-4,...

## Layouts
 - container
 - column
 - display
 - float
 - break
 - position
 - z-index,...

## Borders
 - border
 - divide
 - outline
 - ring

## Effects & Filters
 - box shadow
 - opacity
 - mix blend mode
 - Filters:
 - blur
 - brightness
 - contrast
 - drop shadow
 - grayscale
 - hue-rotate
 ...

## Transitions and Animations
 - transition property
 - transition duration
 - transition timing function
 - transition delay
 - animation

## Transforms
 - scale
 - rotate
 - translate
 - skew
 - transform origin

## Design System
 - create more class like common/utility component
 ```css
 @layer base {
  h1 {
    @apply mb-2 text-3xl font-bold;
  }

  h2 {
    @apply mb-1 text-xl font-semibold;
  }

  a {
    @apply underline text-blue-600 hover:text-purple-500 transition ...
  }

  .btn {
    @apply px-4 py-2 rounded-lg hover:transition hover:duration-300 
    hover:opacity-80 disabled:bg-slate-400/30 hover:disabled:opacity-100 ...;
  }

  .btn-primary {
    @apply bg-blue-500 text-white ...;
  }

  .btn-secondary {
    @apply bg-slate-800 text-white ...;
  }

  input, select {
    @apply 
  }
  input[type="text"] {
    @apply px-1 py-1 border border-slate-500 rounded-lg outline-none;
  }

  input[type="checkbox"] {
    @apply p-2 accent-purple-500;
  }

  label {
    @apply text-sm text-slate-700 font-medium leading-4;
  }
  ...
 ```
## Core Concepts
 - Adding Custom Styles
 ```css
 @layer {

 }
 ```
 - Hover, Focus, and Other States
 `pseudo classes`, `pseudo-elements`, ...
## Dark Mode
 - [Doc](https://tailwindcss.com/docs/dark-mode)