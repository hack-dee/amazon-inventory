# Amazon Inventory Updater

A standalone static web app for updating an Amazon inventory template. The app runs entirely in the browser; uploaded files are not sent to a server.

## Deploy to Cloudflare Pages

1. Push this repository to GitHub.
2. In the Cloudflare dashboard, go to **Workers & Pages** → **Create application** → **Pages** → **Connect to Git** and select this repository.
3. Use these build settings:
   - **Framework preset:** None
   - **Build command:** leave blank
   - **Build output directory:** `.`
4. Select **Save and Deploy**.

Cloudflare Pages will serve `index.html` at the site root. Future pushes to the connected branch will trigger a new deployment.
