# tailwind-css-social-colors
Social color palette for TailwindCSS

Standard social color = Swatch 500

_Shades generated via https://www.tints.dev/_

## Installation
Install the NPM package:

```sh
# Install using npm
npm install --save-dev @hexadog/tailwind-social-colors

# Install using yarn
yarn add -D @hexadog/tailwind-social-colors

# Install using pnpm
pnpm install -D @hexadog/tailwind-social-colors
```

## Usage
Edit your Tailwind config to extend your theme colors.

```js
// tailwind.config.js
const socialColors = require('@hexadog/tailwind-social-colors');

module.exports = {
    theme: {
        extend: {
            colors: { ...socialColors },
        }
    }
}
```

Start using your social colors!
```html
<div class="justify-center items-center w-10 h-10 text-sm font-semibold leading-6 text-facebook-800 rounded-md bg-facebook-100 hover:bg-facebook-500 hover:text-white focus:bg-facebook-500 focus:text-white">
    <svg style="stroke-width: 1.25;" class="flex-shrink-0 h-4 w-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
        <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
        <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3"></path>
    </svg>
</div>
```