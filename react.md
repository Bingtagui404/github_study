# [React](https://react.dev/) * ![](https://camo.githubusercontent.com/7013272bd27ece47364536a221edb554cd69683b68a46fc0ee96881174c4214c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)
React is a JavaScrpt library for building users interfaces.

* Declarative: React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
* Component-Based: Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
* earn Once, Write Anywhere: We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using Node and power mobile apps using [React Native](https://reactnative.dev/)

[Learn how to use React in your project.](https://react.dev/learn)

## Installation
React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:
* Use [Quick Start](https://react.dev/learn) to get a taste of React.
* [Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project)to use as little or as much React as you need.
* [Create a New React App](https://react.dev/learn/start-a-new-react-project)if you're looking for a powerful JavaScript toolchain.
## Documentation
You can find the React documentation on the website.

Check out the Getting Started page for a quick overview.

The documentation is divided into several sections:
* Quick Start
* Tutorial
* Thinking in React
* Installation
* Describing the UI
* Adding Interactivity
* Managing State
* Advanced Guides
* API Reference
* Where to Get Support
* Contributing Guide

You can improve it by sending pull requests to this repository.
# Examples
We have several examples on the website. Here is the first one to get you started:
```
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; we call it JSX. JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.
## Contributing
The main purpose of this repository is to continue evolving React core, making it faster and easier to use. Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving React.

