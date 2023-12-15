# Simple TypeScript Starter | 2023

### Features

- Minimal
- TypeScript v5
- Linting with Eslint and Prettier
- Local development with Nodemon

### Scripts

#### `pnpm install`

Install packages

#### `pnpm run dev`

Starts the application in development using `nodemon` and `ts-node` to do hot reloading.

#### `pnpm run start`

Starts the app in production by first building the project with `pnpm run build`, and then executing the compiled JavaScript at `dist/index.js`.

#### `pnpm run build`

Builds the app at `build`, cleaning the folder first.

#### `pnpm run format`

Format your code.

#### `pnpm run lint`

Lint your code.
