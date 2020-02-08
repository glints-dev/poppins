# glints-poppins

Localized Poppins typeface.

# Usage Instructions

Install the package:

```
npm install --save @glints/poppins  # If using npm
yarn add @glints/poppins            # If using Yarn
```

To use, simply import the package in your project’s entry file e.g.

`index.js`
```js
import '@glints/poppins';
```

# Localization

These are the current languages we support:
- Latin
- Vietnamese

By default, Poppins (Latin) will be loaded. We use the [`unicode-range` CSS descriptor](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/unicode-range) to load SVN Poppins (Vietnamese) only when there are Vietnamese characters. This allows the browser to load the smaller Poppins (Latin) font file unless it needs to display Vietnamese characters.

# Contribution Guidelines

We use [EditorConfig](https://editorconfig.org) to maintain consistent line-ending and indentation rules across all our projects. Ensure that you have the appropriate plugin installed in your preferred editor, or refer to `.editorconfig`

# About Glints

Glints is an online talent recruitment and career discovery platform headquartered in Singapore. It is a platform for young talent to build up their career readiness through internships and graduate jobs; developing skill sets required in different careers.

**P.S.** We deal with quite a number of interesting engineering problems centered on matching the right talent to employers. Sounds interesting? Send your resume to tech@glints.com.
