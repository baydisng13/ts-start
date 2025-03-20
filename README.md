# TS Start

## Overview
TS Start is a basic TypeScript starter project designed for quick and efficient TypeScript development. It includes configurations for linting, formatting, debugging, and continuous integration.

## Features
- TypeScript support
- Biome for linting and formatting
- CI integration with GitHub Actions
- VSCode debugging setup
- Easy deployment to Vercel

## Getting Started

### ### Clone the Repository
```sh
git clone https://github.com/baydisng13/ts-start.git
cd ts-start
```

### Install Dependencies
```sh
pnpm install
```

### Run in Development Mode
```sh
pnpm dev
```

### Build the Project
```sh
pnpm build
```

### Run Compiled Code
```sh
pnpm start
```

### Deploy to Vercel
1. Install Vercel CLI if you haven't already:
   ```sh
   npm install -g vercel
   ```
2. Run the deploy command:
   ```sh
   vercel
   ```
or you can use the button below:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fbaydisng13%2Fts-start&env=GITHUB_TOKEN&envDescription=GitHub%20Token%20for%20GitHub%20Actions%20to%20access%20the%20repository&envLink=https%3A%2F%2Fgithub.com%2Fbaydisng13%2Fts-start%2Fblob%2Fmain%2Fdeploy%2Fgithub-actions-env.example&project-name=ts-start&repository-name=ts-start)

## Debugging with VSCode
The project includes a `.vscode/launch.json` configuration to support debugging.
- **Run & Debug TypeScript**: Launches the `src/index.ts` file using `ts-node`.
- **Attach to Process**: Debugs an already running Node.js process.
- **Debug Compiled JavaScript**: Debugs JavaScript output in the `dist/` folder.

To start debugging, open the `Run and Debug` panel in VSCode and select a configuration.

## Continuous Integration (CI)
This project uses GitHub Actions for CI. It runs Biome checks on every push and pull request to the `main` branch.

### CI Workflow
- **Checkout repository**
- **Set up Node.js and install dependencies**
- **Run Biome checks for linting and formatting**

## Changelog
See the [commit history](https://github.com/baydisng13/ts-start/commits/main) for a list of changes.

## License
This project is licensed under the MIT License.

