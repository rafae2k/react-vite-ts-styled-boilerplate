# React Template（⚡️）

🚀 A React quick start project template powered by vite.

## Feature

- ⚡️ Fast - Build tools based on vite.
- 💄 Prettier - Integrated Prettier to help you format the code.
- 😎 Reliable - Integrated eslint, stylelint, commitlint and jest.
- 🤖 Intelligent - Integrated renovate to help you maintain the dependent version.

## Getting Started

```bash
yarn degit rafae2k/react-vite-ts-styled-boilerplate myapp

cd myapp
```

## Commits

```bash
git add your-files.ts

git commit
```

- Lint staged will run ESlint, Stylelint and Jest and check for errors.

- If everything is Ok it will run commitzen cli, and you could type your commit message. 😎

### Prerequisites

- `yarn` should be installed.
- `git` should be installed (recommended v2.4.11 or higher)

### Available scripts

#### `yarn dev`

Runs the app in development mode.
Open https://localhost:3000 to view it in the browser.

The page will automatically reload if you make changes to the code.
You will see the build errors and lint warnings in the console.

#### `yarn build`

Builds the app for production to the `dist` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

Your app is ready to be deployed.
