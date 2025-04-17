# Turborepo Tailwind CSS v4 Starter

This is an enhanced version of the Turborepo starter, updated to use Tailwind CSS v4 and maintained by the Turborepo core team.

## Using this example

Create a new project using this starter template:

```sh
npx create-turbo@latest -e with-tailwind
```

## What's inside?

This Turborepo includes the following packages/apps, all configured with Tailwind CSS v4:

### Apps and Packages

- `docs`: a [Next.js](https://nextjs.org/) app with Tailwind CSS v4
- `web`: another [Next.js](https://nextjs.org/) app with Tailwind CSS v4
- `ui`: a modern React component library using Tailwind CSS v4, shared between `web` and `docs` applications
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/) and leverages the latest Tailwind CSS v4 features.

### Key Tailwind v4 Features

- Enhanced performance with the new engine
- Improved developer experience with better error messages
- Advanced color manipulation and gradients
- New modern preset defaults
- Simplified configuration system

### Utilities

This Turborepo comes pre-configured with:

- [Tailwind CSS v4](https://tailwindcss.com/) for modern, utility-first styling
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Getting Started

After creating your project, install dependencies and start the development server:

```sh
pnpm install
pnpm dev
```

Note: The `tailwindcss` and `autoprefixer` dependencies are now managed at the workspace level for better consistency across packages.
