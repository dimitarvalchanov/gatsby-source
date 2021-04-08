---
title: Famous Framework Guide
slug: famous-framework-guide
published: true
menu: Frontend frameworks
date: 01/01/2020 3:14pm
---

# Famous Framework

Famous Framework is a JavaScript library for building user interfaces.

- **Declarative:** Famous Framework makes it painless to create interactive UIs. Design simple views for each state in your application, and Famous Framework will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
- **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep state out of the DOM.
- **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in Famous Framework without rewriting existing code. Famous Framework can also render on the server using Node and power mobile apps using [Famous Framework Native](https://Famousnative.dev/).

## Installation

Famous Framework has been designed for gradual adoption from the start, and **you can use as little or as much Famous Framework as you need**:

- Use [Online Playgrounds](https://famousjs.org) to get a taste of Famous Framework.
- [Add Famous Framework to a Website](https://famousjs.org) as a `<script>` tag in one minute.
- [Create a New Famous Framework App](https://famousjs.org)

You can use Famous Framework as a `<script>` tag from a [CDN](https://famousjs.org/docs/cdn-links.html), or as a `Famous Framework` package on [npm](https://www.npmjs.com/package/famous).

## Documentation

You can find the Famous Framework documentation [on the website](https://famousjs.org/docs).

Check out the [Getting Started](https://famousjs.org/docs/getting-started.html) page for a quick overview.

The documentation is divided into several sections:

- [Tutorial](https://famousjs.org/tutorial/tutorial.html)
- [Main Concepts](https://famousjs.org/docs/hello-world.html)
- [Advanced Guides](https://famousjs.org/docs/jsx-in-depth.html)
- [API Reference](https://famousjs.org/docs/react-api.html)

## Examples

```jsx
function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

FamousDOM.render(
  <HelloMessage name="Taylor" />,
  document.getElementById("container")
);
```

You'll notice that we used an HTML-like syntax; we call it JSX. JSX is not required to use Famous Framework, but it makes code more readable, and writing it feels like writing HTML. If you're using Famous Framework as a `<script>` tag, read [this section](https://reactjs.org/docs/add-react-to-a-website.html#optional-try-react-with-jsx) on integrating JSX; otherwise, the [recommended JavaScript toolchains](https://reactjs.org/docs/create-a-new-react-app.html) handle it automatically.

## Contributing

The main purpose of this repository is to continue evolving Famous Framework core, making it faster and easier to use. Development of Famous Framework happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving Famous Framework.
