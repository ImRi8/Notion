# Fullstack Notion Clone:


## This is a repository for Fullstack Notion Clone: Next.js 13, React, Convex, Tailwind

## ✨ Technologies Used

<details><summary><b>Notion</b> is built using the following technologies:</summary>

- [TypeScript](https://www.typescriptlang.org/): TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
- [Next.js](https://nextjs.org/): Next.js is a React framework for building server-side rendered and statically generated web applications.
- [Tailwind CSS](https://tailwindcss.com/): Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces.
- [Convex](https://convex.dev/): Convex is a TypeScript-first ORM for Node.js and the browser.
- [Clerk](https://clerk.dev/): Clerk is a developer-first identity and user management service.
- [ESLint](https://eslint.org/): ESLint is a static code analysis tool for
  identifying problematic patterns found in JavaScript code.
- [Prettier](https://prettier.io/): Prettier is an opinionated code formatter.
- [Shadcn-UI](https://ui.shadcn.com/): Shadcn UI is a React UI library that helps developers rapidly build modern web applications.
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction): Zustand is a small, fast and scalable bearbones state-management solution.
- [BlockNote](https://blocknote.dev/): BlockNote is a Notion-like editor for React.
- [Zod](https://zod.dev/): Zod is a TypeScript-first schema declaration and validation library.
</details><br/>


## Key Features:

- Real-time database  🔗
- Notion-style editor 📝
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

## 🧰 Get Started

To get this project up and running in your development environment, follow these step-by-step instructions.

### 📋 Prerequisites

To install and run this project locally, you would need to have the following installed on your local machine.

- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/get-npm)
- [Git](https://git-scm.com/downloads)

### ⚙️ Installation and Run Locally

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/ImRi8/Notion.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
