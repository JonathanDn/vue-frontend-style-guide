# Frontend Style Guide
This guide is here to set common and recommended baselines to code conventions and best practices that will save time, help maintain focus and increase dev efficiency overall.

## Naming
* File names should be in `kebab-case.vue` format - for `vue files` and `scss files`

## Vue
* `custom events` should be written in `camelCase` format both when declared(emitted) and when listend to in the template.
* Initting variables in the `data` method in a vue component should be done with the `undefined` value.

## CSS
* Write `CSS Variables` for any piece of shared `colors` `layouts` `sizes  and `mixins` at the global scope, or for shared
usage within a component and its descendents write the variables in that parent component.
* Work with `scss` preprocessor, the main reason is to use `nested classes`, by getting use to writing nested classes in every component the HTML DOM tree is inflicted in the scss you are writing. That helps in orientation and in - getting to where you need to add / change more code blazing fast.
* 
