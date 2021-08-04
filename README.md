# click-outside-nuxt

## How to use
1. In nuxt create a new file inside `plugins` dir and paste the code from this file [click-outside.js](./click-outside.js)

1. Register this plugin inside `nuxt.config.js` file
```js
//nuxt.config.js
plugins: [
    '~/plugins/click-outside.js'
  ],
```
3. Use the directive inside your template
```html
<template>
  <div v-click-outside="methodName"></div>
</template>
```
