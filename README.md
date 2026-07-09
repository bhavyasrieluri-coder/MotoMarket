# AutoHub — React App

## Run in VS Code

1. **Unzip / open the folder** `autohub-app` in VS Code (`File > Open Folder`).
2. **Open a terminal** in VS Code: `` Terminal > New Terminal `` (or `` Ctrl+` ``).
3. **Install dependencies** (only needed once):
   ```bash
   npm install
   ```
4. **Start the dev server**:
   ```bash
   npm run dev
   ```
5. Vite will print a local URL, typically:
   ```
   Local: http://localhost:5173/
   ```
   Ctrl+click it (or open it in your browser) to view the app. It hot-reloads as you edit files.

## Project structure

```
autohub-app/
├── index.html          # HTML entry point
├── package.json        # dependencies & scripts
├── vite.config.js       # Vite + React plugin config
└── src/
    ├── main.jsx         # mounts <AutoHub /> into #root
    └── AutoHub.jsx      # the AutoHub page component (edit this)
```

## Requirements

- [Node.js](https://nodejs.org/) 18+ installed (check with `node -v`).
- npm (comes bundled with Node).

## Build for production

```bash
npm run build
```
Outputs static files to `dist/`, which you can deploy anywhere (Netlify, Vercel, GitHub Pages, S3, etc.).
