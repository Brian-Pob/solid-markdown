# SolidJS version of `react-markdown`

***NOTE***

This is obviously a fork of solid-markdown by user andi23rosca. I've made this fork to hopefully continue this project. As of the writing of this edit 2023-02-24,the last commit to this repo was made on 2022-03-21.

The implementation is 90% shamelessly copied from https://github.com/remarkjs/react-markdown.

Changes include:
- Replacing React specific component creation with SolidJS components
- Porting the implementation from javascript with JSDoc types to typescript

Please check the original repo for in-depth details on how to use.

## Installation
```
npm install solid-markdown
```

## Usage

```jsx
import SolidMarkdown from "solid-markdown";

const markdown = `
# This is a title

- here's
- a
- list
`
const App = () => {
  return <SolidMarkdown children={markdown} />
}
```

## TODO
- [ ] Port unit tests from from original library
