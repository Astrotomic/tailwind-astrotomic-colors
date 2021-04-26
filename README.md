# Tailwind Astrotomic Colors

This plugin adds the Astrotomic colours to the Tailwind colour palette.

## Installation

```bash
npm install astrotomic/tailwind-astrotomic-colors
```

**tailwind.config.js**
```javascript
module.exports = {
  plugins: [
      require('tailwind-astrotomic-colors'),
  ],
};
```

## Usage

```html
<div class="space-y-6">
    <button class="bg-astro-astrotomic px-4 py-2 rounded text-white">
        Astrotomic
    </button>
    <button class="bg-astro-moonlight px-4 py-2 rounded text-white">
        Moonlight
    </button>
    <button class="bg-astro-night px-4 py-2 rounded text-white">
        Night
    </button>
    <button class="bg-astro-mit px-4 py-2 rounded text-white">
        MIT
    </button>
    <button class="bg-astro-treeware px-4 py-2 rounded text-white">
        Treeware
    </button>
    <button class="bg-astro-larabelles px-4 py-2 rounded text-white">
        Larabelles
    </button>
</div>
```

Will result in something similar to this:


<img width="560" alt="AstrotomicColours" src="https://user-images.githubusercontent.com/38976391/116099937-5ec8d700-a6a4-11eb-92eb-483e66576440.png">


