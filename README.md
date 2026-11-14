# SupeRR Selector pressure dashboard

This is a self-contained static dashboard. All player data and chart code are embedded in `index.html`; no server, build dependencies, or runtime secrets are needed.

## Deploy on Render

1. Put the contents of this folder in the root of a Git repository you can connect to Render. Keep `index.html` and `render.yaml` at the repository root.
2. In Render, choose **New > Blueprint** and connect that repository. Render reads `render.yaml` and creates a static site.
3. Wait for the first deploy to finish, then open the `onrender.com` URL shown in the Render dashboard.

The dashboard is public when deployed as a Render static site. The embedded data are the public match statistics from the supplied competition data pack.
