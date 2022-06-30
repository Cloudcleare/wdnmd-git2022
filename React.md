# React 

React is a JavaScript library for building user interfaces.

  * **Declarative**:React makes it painless to create interacctive UIs.Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable,simpler to understand,and easier to debug.

  * **Component-Based**:Build encapsulated components that manage their state, then compose them to make complex UIs.Since component logic is written in JavaScript instead of templates,youcan easily pass rich data through your app and keep the state out of the DOM.

  * **Learn Once,Write Anywhever**:We don't make assuptions about the rest of your technology stack,so you can develop new features in React without rewriting existing code.React can also on the server using Node and power mobile apps using [React Native](https://reactnative.dev/)

[Learn how to use React in your porject](https://reactjs.org/docs/getting-started.html)

# Installation

React has been designed for gradual adoption from the start,
and **you can use as little or as much React as you need**:

 * Use [Online Playgrouds](https://reactjs.org/docs/getting-started.html#online-playgrounds)
 to get a taste of React.

 * [Add React to a Website](https://reactjs.org/docs/add-react-to-a-website.html)as a 
`<script>`tag in one minute.
* [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html) if you're looking for a powerful JavaScript toolchain.

You can use React as a `<script>` tag from a [CDN](https://reactjs.org/docs/cdn-links.html) ,
or as a `react` packge on [npm](https://www.npmjs.com/package/react).

# Documentation

You can find the React documentation [on the website](https://reactjs.org/).

Check out the [Getting Stared](https://reactjs.org/docs/getting-started.html)
 page for a quick overview.

 The Documentation is dicided into several sectiongs:
  
  * [Tutorial](https://reactjs.org/tutorial/tutorial.html)

  * [Main Concepts](https://reactjs.org/docs/hello-world.html)

  * [Advanced Guides](https://reactjs.org/docs/jsx-in-depth.html)

  * [API Reference](https://reactjs.org/docs/react-api.html)

  * [where to Get Support](https://reactjs.org/community/support.html)

  * [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)

You can improve it by sending pull requests to [this repository](https://github.com/reactjs/reactjs.org).

# Examples

We have several examples [on the website](https://reactjs.org/).
Here is the frist one to get you started:

```JavaScript
import {createRoot} from 'react-dom/client';

function HelloMessage({ name })  {return <div>Hello (name)</div>;}

const root = createRoot(document.getElementById('container'));

root.render(<HelloMessage name="Taylor"/>);
```

This example will render "Hello Talor" into a container on the page.

You'll notice that we used an HTML-like syntax;
[we call it JSX](https://reactjs.org/docs/introducing-jsx.html).
JSX is not required to use React,but it make codes more readable an writing HTML.
If you're using React as a `<script> ` tag,
read [this section](https://reactjs.org/docs/add-react-to-a-website.html#optional-try-react-with-jsx) 
on integrating JSX;otherwise,the [recommended JavaScipt toolchains](https://reactjs.org/docs/create-a-new-react-app.html) 
handle it automatically.

# Contributing

The main purpose of this repository is to continue evolving React core,
making it faster and easier to use.Development of React happens in the open on GitHub,
and we are grareful to the community for contributing bugfixes 
and improvements.Read below to learn how you can take part in improving React.

## [Code of conduct](https://opensource.fb.com/showcase)

Facebook has adopted a Code of Conduct that 
we expect project participants to adhere to.
Please read [the full text](https://opensource.fb.com/code-of-conduct/) so that you can 
understand what actions will and will not be tolerated.

## [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)

Read our [contributing guide](https://reactjs.org/docs/how-to-contribute.html) 
to learn about our development poocess,how to propose bugfixes 
and improvements,and how to build an test your changes to React.

## Good Frist lssues

To help you get your feet wet and get you familiar with our 
contribution process,
we havea list of [good frist issues](https://github.com/facebook/react/labels/good%20first%20issue) 
that contain bugs that have a relatively limited scope.
This is a great place to get started.

## license

React is [MIT licensed](https://github.com/facebook/react/blob/main/LICENSE).