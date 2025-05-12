### What is Redux?

- JS library for predictable and maintainable global state management.
- Helps to write applications that behave consistently, run in different environments(client, server and native).
- We can use Redux together with React which is tiny(2kB) but has a large ecosystem of addons available.
- **Redux Toolkit** is a wrapper around **Redux core** which is officially recommended.
- **RTK** includes utilities that help simplify many common use cases including:
  - store setup
  - creating reducers and writing immutable update logc
  - creating entire **slices** of state at once.

### Setup

- RTK toolkit: (Run any of them)

```
npm install @redujs/toolkit
yarn add @reduxjs/toolkit
```

- Create a React Redux App: (Run any of them)
```
npx degit reduxjs/redux-templates/packages/vite-template-redux-my-app
npx create-next-app --example with-redux my-app
```

- Redux Core
```
npm install redux
yarn add redux
```
