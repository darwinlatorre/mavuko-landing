# Mavuko Landing

Public-facing Mavuko website built with Angular 21 and SCSS.

## Requirements

- A Node.js version compatible with Angular 21
- npm (the project declares version 11.16.0)

## Install and run

```sh
npm ci
npm start
```

Open `http://localhost:4200/`. The development server reloads when source files
change.

## Build

```sh
npm run build
```

The default build uses the production configuration and writes output to `dist/`.

## Tests

Run the configured unit tests without watch mode:

```sh
npm test -- --watch=false
```

No end-to-end test target is currently configured.

## Structure

```text
src/                Application source, styles and environment configuration
public/             Static assets
angular.json        Angular project and build configuration
package.json        Dependencies and npm scripts
tsconfig.json       TypeScript configuration
```
