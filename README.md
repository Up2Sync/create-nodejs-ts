# @up2sync/starter-output
A fork of ["Node.js Starter ToolKit" by Vitor Hugo Salgado](https://github.com/vitorsalgado/create-nodejs-ts)

<h1 align="center">Node.js Starter ToolKit</h1>

<p align="center">
    <i>Starter Project for a Node.js application using <strong>TypeScript</strong> with all boring stuff already configured.</i>
</p>

<p align="center">
  <a href="https://github.com/vitorsalgado/create-nodejs-ts/actions/workflows/ci.yml">
    <img src="https://github.com/vitorsalgado/create-nodejs-ts/actions/workflows/ci.yml/badge.svg" alt="GitHub Action Status" />
  </a>
  <a href="https://www.npmjs.com/package/create-nodejs-ts">
    <img src="https://img.shields.io/npm/v/create-nodejs-ts.svg?logo=npm&logoColor=fff&label=NPM+package&color=limegreen" alt="npm" />
  </a>
  <a href="https://nodejs.org/en/">
    <img src="https://img.shields.io/node/v/create-nodejs-ts" alt="Node Min Version" />
  </a>
  <a href="https://github.com/prettier/prettier">
    <img src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat" alt="Prettier"/>
  </a>
  <a href="https://conventionalcommits.org">
    <img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" alt="Conventional Commits"/>
  </a>
</p>

## Overview

Starter project for **Node.js** applications using **TypeScript** with Test, Lint, Code Style already configured. Take a
look below for all the tooling available in this repository.  
The preferable way to use this boilerplate is using `npx` command. You can use `npm init` too.  
Use the following commands to bootstrap a new project:

### NPX

```
npx create-nodejs-ts --no --app=your-app
```

### NPM Init

```
npm init nodejs-ts -- --app=your-app
```

Without parameters, the project will be created on a folder **my-app** in the same directory where you executed the
command.  
All parameters available:

```
--destination=<FOLDER_DESTINATION> Defaults to the current directory
--app=<APP_NAME> Defaults to my-app
```

The final folder will the parameter `destination` concatenated with parameter `app`.

## Tooling

- TypeScript
- EsLint
- Husky
- Commit Lint
- Lint Staged
- Prettier
- Standard Version
- Nodemon
- Docker | Docker Compose

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fvitorsalgado%2Fnodejs-boilerplate.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fvitorsalgado%2Fnodejs-boilerplate?ref=badge_shield)

This project is [MIT Licensed](LICENSE).
