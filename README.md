# Notes for Vue.js

- The App.vue file is the single-file component. It houses all the JavaScript, HTML, and CSS. (This is the main selling point of Vue)

- The `<script>` tag is used to write functions. You can then use it in the `<template>` tag. You can make a JavaScript file containing the 
App.vue and a CSS file if you want to seperate for better readability.

- The mustache tag or `{{ msg }}` is used for text interpolation. (Most of the syntax sugar can be read on [Vue.js](https://vuejs.org/guide/essentials/template-syntax.html#using-javascript-expressions "Vue.js documentation"))

- The imported words from vue are called hooks. (React has them as well)

- Make sure to look up `v-model` which can bind data both ways and `v-bind` which can bind only one way making the original unchanged.
* reactive data binding is a strength of vue.
