# React + TypeScript + Vite

This template provides a starting point for building React applications using Vite as the build tool, TypeScript for type safety, Storybook for component development, Tailwind CSS for styling, ESLint and Prettier for code formatting and linting, and lint-staged with husky for pre-commit hooks.

## Features

- **Vite**: A fast, modern build tool for web development.
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A statically typed superset of JavaScript that compiles to plain JavaScript.
- **Storybook**: An open-source tool for developing UI components in isolation for React, Vue, and Angular.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **ESLint**: A pluggable linting utility for JavaScript and TypeScript.
- **Prettier**: An opinionated code formatter.
- **lint-staged**: Run linters on git staged files.
- **husky**: Git hooks made easy.

## Getting Started

To create a new project based on this template, you can use [degit](https://github.com/Rich-Harris/degit) to clone it without Git history:

```bash
npx degit EmilieLny/react-template-tailwind my-react-app
```

After cloning the template, navigate to the newly created directory:

```bash
cd my-react-app
```

Then, install the dependencies:

```bash
npm install
# or
yarn
```

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm run build`

Builds the app for production to the `dist` folder.

### `npm run serve`

Serves the production build from the `dist` folder.

### `npm run lint`

Runs ESLint to lint the TypeScript code.

### `npm run lint:fix`

Runs ESLint with the `--fix` option to automatically fix linting issues.

### `npm run format`

Formats the code using Prettier.

### `npm run storybook`

Starts the Storybook server.
Open [http://localhost:6006](http://localhost:6006) to view it in the browser.

### `npm run build-storybook`

Builds the Storybook as a static site for production to the `storybook-static` folder.

## Project Structure

The project structure is organized as follows:

```
my-react-app/
│
├── src/
│   ├── components/
│   │   ├── Button/
│   │   │   ├── Button.tsx
│   │   │   └── Button.stories.tsx
│   │   └── ...
│   ├── App.tsx
│   └── index.tsx
│
├── .storybook/
│   └── main.js
│
├── .eslintrc.js
├── .prettierrc.js
├── .lintstagedrc.js
├── .husky/
│   └── pre-commit
│
├── package.json
└── vite.config.ts
```

## Dependencies

- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Vite](https://vitejs.dev/): A build tool that aims to provide a faster and leaner development experience for modern web projects.
- [TypeScript](https://www.typescriptlang.org/): A typed superset of JavaScript that compiles to plain JavaScript.
- [Storybook](https://storybook.js.org/): An open-source tool for developing UI components in isolation for React, Vue, and Angular.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.
- [ESLint](https://eslint.org/): A pluggable linting utility for JavaScript and TypeScript.
- [Prettier](https://prettier.io/): An opinionated code formatter.
- [lint-staged](https://github.com/okonet/lint-staged): Run linters on git staged files.
- [husky](https://github.com/typicode/husky): Git hooks made easy.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
