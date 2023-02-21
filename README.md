# NxPlayground

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **This workspace has been generated by [Nx, a Smart, fast and extensible build system.](https://nx.dev)** ✨

## Install Project
1. Run `npx create-nx-workspace nx-playground --preset=nest` to create a nx workspace.
2. Run `npm install -g nx` to enable nx cli

## Development server

Run `nx serve backend` for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

### Failed to run development server (Optional)
Run `nx report` to find the error.

In my case @nrwl/node was "not found", so I just installed it with: 
`npm i @nrwl/node`.

## Understand this workspace

Run `nx graph` to see a diagram of the dependencies of the projects.

## Remote caching

Run `npx nx connect-to-nx-cloud` to enable [remote caching](https://nx.app) and make CI faster.

## Further help

Visit the [Nx Documentation](https://nx.dev) to learn more.
