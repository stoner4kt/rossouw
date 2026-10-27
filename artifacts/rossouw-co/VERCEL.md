# Importing Rossouw & Co. into Vercel

1. Push this repository to GitHub, then import it as a new Vercel project.
2. Set the Vercel **Root Directory** to `artifacts/rossouw-co`.
3. Keep the detected pnpm package manager. The repository pins pnpm in the root `package.json`.
4. The included `vercel.json` sets the build command to `pnpm run build` and the output directory to `dist/public`.
5. No environment variables or server functions are required to build and serve this static site.

The Vite configuration defaults to `/` and a local development port when Replit-specific environment variables are not present. The Replit preview continues to use its injected values.

The Google Analytics and Search Console integrations remain inactive until their real IDs are added. Connect the production domain before verifying the property or submitting the sitemap.
