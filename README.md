<p align="center"><img src="https://i.ibb.co/9gjsz5V/starwars.png"></p>

# Front-end Challenge - Star Wars API

[![Greenkeeper badge](https://badges.greenkeeper.io/stone-payments/pos-mamba-app-template.svg)](https://greenkeeper.io/)

## Introduction
Hello! Now you can better control your customers on the space station.

#### Yellow Button
> Show a single random Star Wars character.
<p align="center"><img src="https://i.ibb.co/CmvsGvY/generate.gif"></p>

#### Blue Button
> Prints a single Star Wars character.
<p align="center"><img src="https://i.ibb.co/2vdpvcy/print.gif"></p>

#### Black Button
> Show a list of all Star Wars characters that have passed through here.
<p align="center"><img src="https://i.ibb.co/8jFjzHQ/list.gif"></p>

---
### Mamba App template
>A complete project template for building [Mamba](https://github.com/stone-payments/pos-mamba) apps.

### Requirements

Make sure all dependencies have been installed before moving on:

- [Node.js](http://nodejs.org/) >= v8.11.3

Recommended:

- [@mamba/cli](https://www.npmjs.com/package/@mamba/cli)

### Building and deploying to the `POS`

1. Generate the *production* app bundle

```shell
# With the @mamba/cli
mamba app build

# Without the @mamba/cli
npm run build
```

This will generate the `dist/bundle.pos` directory and a `dist/bundle.pos.tar.gz` file, which both contains your Mamba app.

2. Start the local http server

```shell
npm run serve # Starts the local http server
```

3. Open the `Develop` app and insert your local server ip and the app will automatically look for the `dist/bundle.pos.tar.gz` and install it.

### Npm Commands

- `npm run start` - Start the dev server;
- `npm run serve` - Start a local http server;
- `npm run build` - Build the production bundle;
- `npm run build:dev` - Build the development bundle;
- `npm run build:analyze` - Analyze the final bundle;
- `npm run lint` - Lint all style and script files;
- `npm run format` - Format all style and script files;

### Documentation

- [Svelte](https://svelte.technology/guide)
- [Mamba SDK](https://mambasdk-docs.stone.com.br/)
