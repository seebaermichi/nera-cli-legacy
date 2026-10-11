# Nera Cli

> [!WARNING]
> **Deprecated and archived.** This is the old `nera-cli` (it scaffolds a site by cloning the generator) and is no longer maintained. Use `npx @nera-static/nera new <name>` instead.
> Current Nera: [nera.js.org](https://nera.js.org) · [`@nera-static/nera`](https://www.npmjs.com/package/@nera-static/nera) · [seebaermichi/nera](https://github.com/seebaermichi/nera).
Nera cli is a tool to initialize and work on projects which are build with  
light weight static site generator [Nera](https://github.com/seebaermichi/nera).

## Install
```shell
npm install -g nera-cli
```

## Usage
To initialize a new Nera project, just run
```shell
nera init my-project
```
> This will clone the nera repo and render the initial pages.

To start working on a Nera project, use
```shell
nera start my-project
```
> This will render the pages, start the local server and the nodemon watcher.

