<div align="center">
  <h1><img height="38px" width="44px" style="height: 38px; max-width: 44px" src="https://raw.githubusercontent.com/jpmorganchase/modular/main/docs/img/modular-hero.svg"> &nbsp; Modular</h1>

  <p><strong>Scaled Web Engineering</strong>. Where Libraries, Views & apps coexist together and tooling is a first-class citizen.</p>
</div>

---

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?)](https://github.com/jpmorganchase/modular/blob/main/CONTRIBUTING.md)
[![NPM version](https://img.shields.io/npm/v/modular-scripts.svg)](https://www.npmjs.com/package/modular-scripts)
![Static](https://github.com/jpmorganchase/modular/actions/workflows/static.yml/badge.svg)
![Tests](https://github.com/jpmorganchase/modular/actions/workflows/test.yml/badge.svg)
[![Coverage](https://coveralls.io/repos/github/jpmorganchase/modular/badge.svg?branch=main)](https://coveralls.io/github/jpmorganchase/modular?branch=main)

`modular` is a collection of tools and guidance to enable UI development at
scale. It is derived from work at JP Morgan to enable development in a single
repository by many teams.

It provides a `modular` CLI to scaffold and develop a new application from
scratch, as well as commands to add and manage further modules.

## Philosophy

`modular` believes the burden to learn a "Framework" with proprietary APIs in a
rapidly evolving landscape is an inhibitor to **scaled web engineering**.

There is already a very strong set of **Language Constructs, Frameworks and
Tooling** that the front end community is rallying around like `TypeScript`,
`ES6 Modules`, `React`, `Parcel`, `Webpack`, `GitHub Actions`, `Jest`,
`Workspaces` etc.

Scaled Engineering requires a few more Frameworks, Libraries and Tools that are
not yet first class citizens in the world of Front End Engineering like
**Universal Data Fetching**, **Feature Flags**, **Analytics Capture**,
**Security**, **Deployment** etc.

`modular` attempts to bring the best Language Constructs, Libraries, Frameworks
and Tooling together to establish a set of patterns and definitions to enable
**Monorepo** based engineering.

## Getting Started

```bash
  yarn create modular-react-app my-new-modular-project [--verbose] [--prefer-offline] [--repo]
```

Bootstraps a new project, configured to use
[Yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces/).

This also creates a workspace named 'app' which is a new modular app written in
[TypeScript](https://www.typescriptlang.org/).

It supports three flags:

- `--verbose` enables verbose `yarn` and `modular` logging.
- `--prefer-offline` will prefer locally cached `node_modules` versions over
  those from your remote registry.
- `--repo <value>` will toggle whether a new `git` repo is created and the
  initial files committed.

## Commands

More documentation about modular commands is
[here](https://github.com/jpmorganchase/modular/tree/main/docs/).

## Configuration

Modular is based around the idea of minimal configuration - however
documentation for the options available is
[here](https://github.com/jpmorganchase/modular/tree/main/docs/configuration.md).
