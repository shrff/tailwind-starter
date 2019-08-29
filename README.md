# tailwind-starter
A simple demo of Tailwind CSS with PurgeCSS setup for the team at Genius Division. It's a simple about me page that is used on [jamessheriff.com](https://www.jamessheriff.com/)

## Get started
1. Clone repository
2. `npm install`
3. `npm run watch`
4. Profit

## What to look at
- `tailwind.config.js` is the config for Tailwind where you can enable (and disable) certain features.
- `postcss.config.js` is the config which compiles the Tailwind CSS into the build folder. PurgeCSS config is wrapped in an environment variable so that it doesn't run all the time.
- `package.json` contains the build script config. 

## Developing and building
- `npm run watch` is used in development and compiles CSS and doesn't purge the CSS.
- `npm run production` strips unused CSS ready for production.
