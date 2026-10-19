# React Router Lab

## Aim
React Router Lab — a React practical built with Vite, React, React Router DOM where relevant, and Tailwind CSS v4.

## Concepts used
- React functional components and JSX
- Component-based UI and responsive utility-first styling
- React Router DOM
- Form state, validation, and interactive feedback where relevant

## Requirements
- Node.js 20.19+ or 22.12+ recommended
- npm

## Run the project
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

Each practical is independent. Open its folder in VS Code and run the commands from that folder.


## Router notes
- `BrowserRouter`: normal history-based URLs, usually needs server fallback configuration in production.
- `HashRouter`: route is stored after `#`, so the server receives the same path for each route.
- `MemoryRouter`: history is stored in memory and does not change the address bar.
- `StaticRouter`: intended for server rendering; this project explains it with a code example rather than pretending it is a normal browser router.
