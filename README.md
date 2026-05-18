# tallerallocation

Taller Allocation Landing Page.

## Development

```bash
npm install
npm run dev
```

Opens at http://localhost:5173.

## Component docs

```bash
npm run storybook
```

Opens at http://localhost:6006.

## Stack

HTML + CSS + JS. Vanilla, single-file (`index.html`). No framework, no build step for the LP itself. Vite serves the static files in development with HMR.

Storybook 10 (HTML + Vite preset) documents component primitives in parallel. Vitest, Playwright and `@storybook/addon-a11y` cover testing and accessibility. Chromatic handles visual regression.

Hosting on Vercel.

## Project

Strategy, copy, structure and discovery documents live in the parent folder.
