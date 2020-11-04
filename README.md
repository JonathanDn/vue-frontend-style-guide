# Frontend Style Guide
This guide is here to set common and recommended baselines to code conventions and best practices that will save time, help maintain focus and increase dev efficiency overall.

## Architecture
* 

## Project Sturcture
* divison of `src` to `frontend` and `backend`?
* Where we put `components` at what structure, what hirearchy.
* Where do we put `shared styles`
* Where do we put `shared logic` like `util` or `services` or `vue components` that are shared like a Shared UI folder(based on a design system)
* When to divide to `.scss` file (After certain amount of lines of code) 

## Naming
* File names should be in `kebab-case.vue` format - for `vue files` and `scss files`

## Logic (Vue)
* `custom events` should be written in `camelCase` format both when declared(emitted) and when listend to in the template.
* Initting variables in the `data` method in a vue component should be done with the `null` value. (**NOT** using `undefined` as it collides with JS defauls occasionally)
* When writing components keep in mind the difference between `smart` and `dumb` components or `logic-handling` and `plane views`(non logic-handling) components.

## Template (HTML)
* When your html tag has `3 attributes` that is the time to open new lines and stack them vertically instead of horizontally.

## Styling (SCSS)
* Work with `scss` preprocessor, the main reason is to use `nested classes`, by getting use to writing nested classes in every component the HTML DOM tree is inflicted in the scss you are writing.(That helps in orientation and in - getting to where you need to add / change more code blazing fast. `scss variables` help with things `css variables` do not yet support like using variables in `media queries`)
* Write `SCSS Variables` for any piece of shared `colors` `layouts` `sizes  and `mixins` at the global scope, or for shared
usage within a component and its descendents write the variables in that parent component.
* `<style>...` tags inside `.vue` components should be created in default with `scoped` and `lang="scss"` attributes.
* 
