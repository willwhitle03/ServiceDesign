Decision Ledger prototype · website files
=========================================

This folder is the whole site. Open index.html in a browser to try it locally.
No server code, no build step.

UPDATE YOUR SITE
  Netlify: open your site > Deploys > drag this whole folder onto the box.
  Vercel / GitHub: replace the old files in your repository with everything
  in this folder (keep the img folder), then commit. Vercel redeploys on its own.

WHAT'S INCLUDED
  index.html                   the prototype (front door, carousel, Research,
                               Solution, presentation, demos, lead review)
  img/                         the 15 carousel snapshots
  support.js                   the runtime that renders the page
  react / react-dom .min.js    React 18.3.1, which the runtime uses

NOT INCLUDED
  The multi-board canvas and its comments (Claude viewer features).
