# Turborepo Tailwind CSS v4 Starter

This is an enhanced version of the Turborepo starter, updated to work with the latest Tailwind CSS (v4), featuring a restructured setup and up-to-date configuration for modern development.

## Using this example

Create a new project using this starter template:

```sh
npx create-turbo@latest -e with-tailwind
```

## What's inside?

This Turborepo includes the following packages/apps, all configured for compatibility with Tailwind CSS v4:

### Apps and Packages

- `docs`: a [Next.js](https://nextjs.org/) app with Tailwind CSS v4
- `web`: another [Next.js](https://nextjs.org/) app with Tailwind CSS v4
- `ui`: a modern React component library using Tailwind CSS v4, shared between `web` and `docs` applications
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/) and leverages the latest Tailwind CSS v4 features.

### Key Tailwind v4 Features

- Up-to-date configuration for Tailwind CSS v4
- Improved project structure for easier maintenance
- Consistent workspace-level dependency management
- Enhanced performance with the new engine
- Improved developer experience with better error messages
- Advanced color manipulation and gradients
- New modern preset defaults
- Simplified configuration system

### Utilities

This Turborepo comes pre-configured with:

- [Tailwind CSS v4](https://tailwindcss.com/) for utility-first styling
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Getting Started

After creating your project, install dependencies and start the development server:

```sh
pnpm install
pnpm dev
```

Note: The `tailwindcss` and `autoprefixer` dependencies are managed at the workspace level for consistency across packages.
