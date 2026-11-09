Decision Ledger prototype · website files
=========================================

This folder is the whole site. Open index.html in a browser to try it locally.
Everything runs in the browser: no server code, no build step.

PUT IT ONLINE (pick one)

Netlify Drop (fastest, about 1 minute)
  1. Go to app.netlify.com/drop and sign in (free).
  2. Drag this whole folder onto the page.
  3. Netlify gives you a live URL. Rename it in Site settings if you like.
  To update later: open the site in Netlify > Deploys, and drag the new folder in.

GitHub Pages (free, good for a portfolio)
  1. Create a new public repository on github.com.
  2. Upload the four files in this folder (Add file > Upload files).
  3. Settings > Pages > Source: "Deploy from a branch", branch "main", folder "/ (root)".
  4. Your site appears at https://<your-username>.github.io/<repo-name>/ in a minute or two.

Custom domain (optional)
  Both hosts let you connect a domain you own (for example willdesigns.com)
  in their domain settings.

WHAT'S INCLUDED
  index.html                   the prototype (front door, Research, Solution,
                               presentation, video demo, interactive demo, lead review)
  support.js                   the runtime that renders the page
  react / react-dom .min.js    React 18.3.1, which the runtime uses

NOT INCLUDED
  The multi-board canvas and its comments. Those are features of the Claude viewer.
  Share the claude.ai artifact link for that view.
