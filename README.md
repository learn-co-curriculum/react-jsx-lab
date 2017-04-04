# React JSX Lab

## Overview

In this lab, you'll define component with JSX and compile Javascript. 

## Setup

We'll focus on writing JSX code to render components. Make sure you export your components; otherwise the
tests won't be able to access your code!

## Registration form
1. In the `components/RegistrationForm.js` file, create an ES2015 React component called `RegistrationForm`.
2. This component should contain the following:
    1. One `<form>` element
    2. Two `<input>` elements — one has a `text` type, the other one is a `password`
    3. One `<button>` element with the `submit` type
    
>Note: In JSX, all tags must close. A good example of where this can cause problems is the `<input>` tag. Writting the tag like this will throw an error if you're not following it somewhere with a `</input>`. More often than not though, you don't need to put anything in between the opening and closing input tags. When that's the case, you can just use a self closing tag like this: `<input />`
    
## Webpage
1. In the `components/FillerText.js` file, create an ES2015 React component called `FillerText`.
2. This component should be a paragraph containing the following text: `I am a filler text. I can be used to fill your
screen. Amazing!`.
3. In the `components/Webpage.js` file, create an ES2015 React component called `Webpage`.
4. This component should contain a title with the text `The world's coolest webpage`.
5. This component should also contain _two_ instances of the `FillerText` component.

## Resources
- [Browserify][browserify]
- [Babel](http://babeljs.io/)
- [Babelify][babelify]
- [JSX](https://facebook.github.io/react/docs/jsx-in-depth.html)

[browserify]: https://github.com/substack/node-browserify
[babelify]: https://github.com/babel/babelify
