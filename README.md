# Task list with Next.js and Graphql
## Table of Contents
- [Task list with Next.js and Graphql](#task-list-with-nextjs-and-graphql)
  - [Table of Contents](#table-of-contents)
  - [Installing Next.js](#installing-nextjs)
  - [tsc CLI Options](#tsc-cli-options)
  - [Apollo Client](#apollo-client)
## Installing Next.js
[Next.js](https://nextjs.org/docs/getting-started) is a flexible React framework that gives you building blocks to create fast web applications.

```sh
npx create-next-app@latest --typescript
```
## tsc CLI Options
If you’re looking for more information about the compiler options in a tsconfig, check out the [Compiler Options](https://www.typescriptlang.org/docs/handbook/compiler-options.html).

## Apollo Client
[Apollo Client](https://www.apollographql.com/docs/react/get-started/) is a comprehensive state management library for JavaScript that enables you to manage both local and remote data with GraphQL. Use it to fetch, cache, and modify application data, all while automatically updating your UI.
More details: [Apollo Client in Next.js](https://www.apollographql.com/blog/apollo-client/next-js/next-js-getting-started/), [Next.js with Apollo Example](https://github.com/vercel/next.js/tree/canary/examples/with-apollo)

```sh
npm install @apollo/client graphql
```