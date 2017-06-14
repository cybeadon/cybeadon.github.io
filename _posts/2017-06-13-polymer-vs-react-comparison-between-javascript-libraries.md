---
layout: post
title: Polymer vs React - Comparison between JavaScript Libraries
categories: Web, JavaScript
tags: Polymer, React, JavaScript, HTML, CSS, Web Components
---

With recent advancements in technologies, the web no longer serves just static content. Thanks to JavaScript, websites became web apps providing dynamic content. There are lots of JavaScript libraries and frameworks available in the market for building dynamic web apps. 

Some of the popular libraries like `Polymer` and `React` allows developers to create components composed of data and UI. Having experience in both libraries we will compare both of them in this article.

### React
[React](https://facebook.github.io/react/){:target="_blank"} is a JavaScript library developed by [facebook](https://code.facebook.com/){:target="_blank"} that helps developers to build UI components declaratively. React components can be written in [JSX](https://facebook.github.io/react/docs/introducing-jsx.html){:target="_blank"} which is a syntax extension of JavaScript. JSX enables user to write HTML within JavaScript.

### Polymer
[Polymer](https://www.polymer-project.org/){:target="_blank"} is a JavaScript library developed by [Google](https://developers.google.com){:target="_blank"} that helps developers to create reusable HTML elements based on [Web Components](https://www.webcomponents.org/introduction){:target="_blank"} standards. Polymer allows developer to harness the power of Web Components for building a future proof apps.

---

The below table indicates a comparison between React and Polymer.

Feature | Polymer | React
-|-|-
&nbsp; | ![Polymer Logo](https://www.polymer-project.org/images/logos/p-logo.png){:height="160px"} | ![React Logo](https://facebook.github.io/react/img/logo.svg){:height="160px"}
**Popularity** (Number of GitHub Stars) | <a class="github-button" href="https://github.com/polymer/polymer" data-icon="octicon-star" data-show-count="true" data-size="large" aria-label="Star polymer/polymer on GitHub">Star</a> | <a class="github-button" href="https://github.com/facebook/react" data-icon="octicon-star" data-show-count="true" data-size="large" aria-label="Star facebook/react on GitHub">Star</a>
**Server Side Rendering** | No | Yes (with [Node.js](https://nodejs.org/){:target="_blank"})
**Compliant to Web Components standard** | Yes | No. 
**Data Flow** | Between parent and child components (two-way binding)  | Only from parent to child component (one-way binding)
**Support Channel** | [slack](https://polymer.slack.com){:target="_blank"}, [stack overflow](https://stackoverflow.com/questions/tagged/polymer){:target="_blank"}  | [discord](https://discord.gg/0ZcbPKXt5bZjGY5n){:target="_blank"}, [forum](https://discuss.reactjs.org/){:target="_blank"}, [stack overflow](http://stackoverflow.com/questions/tagged/reactjs){:target="_blank"}
**Tooling Support** | Less | Huge
**Browser Support** | Chrome (Native). <br /> Firefox, Safari 9+, IE 11+,  and Edge (Using polyfills) | Chrome, Firefox, Safari, IE 9+, and Edge (By compiling ES6 to ES5)
**Notable Sites Using** | [Facebook](https://facebook.com){:target="_blank"}, [Feedly](https://feedly.com){:target="_blank"}, [Fiverr](https://www.fiverr.com/){:target="_blank"}, [Flipkart](https://www.flipkart.com/){:target="_blank"}, [Instagram](https://instagram.com){:target="_blank"}  | [Google Translate Community](http://translate.google.com/community){:target="_blank"}, [Google Music](https://play.google.com/music/listen){:target="_blank"}, [EA](http://www.ea.com/){:target="_blank"}, [Divshot](https://divshot.com){:target="_blank"}, [Youtube Gaming](https://gaming.youtube.com/){:target="_blank"}

### Which library should you use?
Polymer provides an easy way of creating custom components and adheres to Web Components standard wheres react takes advantage of its `virtual DOM` implementation which renders the DOM blazing fast.

If you want to build future-proof apps that support modern browser, Polymer is your choice. If you want to build an app with rich data, you can go for React. Also check for the availability of community built components for [React](https://www.npmjs.com/browse/keyword/react){:target="_blank"} and [Polymer](https://www.webcomponents.org/){:target="_blank"}, before starting to build it on your own.

### Final Thoughts
Using Polymer components inside a React component and vice versa is practically possible, but not usually preferred. More information available about using Web Components within React is available in React [documentation](https://facebook.github.io/react/docs/web-components.html){:target="_blank"} page.

The quality of the application that you build brings more value irrespective of the framework that you use. So try focusing more on building the application rather than focusing on the library that you use. Want to explore more JavaScript front-end frameworks? Checkout this [collection](https://github.com/showcases/front-end-javascript-frameworks){:target="_blank"} of JavaScript frameworks build by [GitHub](https://github.com){:target="_blank"}.

Decided a library to use in your next project? Share your thoughts in the comments section below.

<script async defer src="https://buttons.github.io/buttons.js"></script>
