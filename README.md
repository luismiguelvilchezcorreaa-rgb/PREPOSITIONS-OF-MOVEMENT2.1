# Movement Mission A2

Interactive English practice platform for **prepositions of movement**.

## Technology
- TypeScript
- Vite
- CSS
- No framework required

## Local use
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## GitHub Pages
This project includes a GitHub Actions workflow.

1. Create a new GitHub repository.
2. Upload all project files.
3. In GitHub go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **GitHub Actions**.
5. Push to the `main` branch.
6. The workflow will build and publish the site automatically.

`vite.config.ts` uses `base: "./"` so assets work correctly on GitHub Pages.
