# Batool Proposal

A site: "Do you like me?" with a **No** button that dodges the cursor/taps
(and floats away a little each time), and a **Yes** button that leads to the reveal —
Batool's photo and the proposal page.

Two files, both need to go up together:
- `index.html`
- `batool.jpeg` (must keep this exact filename, or update the `src="batool.jpeg"` line in `index.html` if you rename it)

## Deploy in 2 minutes

### Option A — GitHub Pages
1. Create a new repo, e.g. `batool-proposal`.
2. Upload **both** `index.html` and `batool.jpeg` to the repo root (drag-and-drop on github.com works fine — do them in the same upload so nothing's missing).
3. Go to **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   pick `main` and `/ (root)`, then Save.
4. Your site goes live at:
   `https://<your-username>.github.io/batool-proposal/`

### Option B — Vercel
1. Go to vercel.com → **Add New → Project → Deploy without Git** (or connect the GitHub repo above).
2. Drop in the whole folder (both files) — don't upload just `index.html` on its own or the photo won't load.
3. Vercel gives you a live URL like `https://batool-proposal.vercel.app` — you can
   rename the project to `batool-proposal` in the Vercel dashboard so the URL matches.

That's it — no build step, no dependencies to install, just the two files.
