# Angular Lifecycles Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A free visual reference for how Angular applications run, written for developers who already know Angular. Checked against Angular 22 in November 2026.

**[Open the guide](https://angular-lifecycles.vercel.app)**

## What's inside

| Page | Covers |
|---|---|
| [Modern application lifecycle](https://angular-lifecycles.vercel.app) | Bootstrap, signals, zoneless change detection, lazy loading, resources and router guards |
| [Dependency injection](https://angular-lifecycles.vercel.app/angular-di-injection-context.html) | Injection context, injector hierarchy, service scopes, advanced providers and testing |
| [Lifecycle hooks](https://angular-lifecycles.vercel.app/angular-traditional-lifecycles.html) | The eight hooks, execution order, common mistakes, testing and a cheat sheet |

## How it's built

The guide is three static HTML pages. The flowcharts use [Mermaid](https://mermaid.js.org), loaded from a CDN. There's no Angular app, build step or dependency to install, and the code samples are for reading rather than running.

## Run it locally

```bash
git clone https://github.com/aliroshandev/angular-lifecycles.git
cd angular-lifecycles/demo
npx serve .
```

You can also open the HTML files directly, but the "Back" links that point to `/` only work from a server.

## Corrections

Angular changes quickly. If something is wrong or out of date, please [open an issue](https://github.com/aliroshandev/angular-lifecycles/issues) and include a link to the Angular docs.

## License

MIT
