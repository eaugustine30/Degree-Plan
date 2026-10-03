# Degree Sprint

A daily progress page for my degree sprint, Oct 1 – Dec 18, 2026: today's plan, what's checked off, the week, and every course and milestone.

**Page:** https://eaugustine30.github.io/Degree-Plan/

## How it works
- `index.html` is the whole page. The plan is built in.
- `progress.json` here is the starting point. Live progress is saved to the same file on the **`progress`** branch. The page creates that branch the first time something is checked off, so uploading a new `index.html` later never erases progress.
- Everyone with the link sees progress within a couple of minutes. Nothing on the page identifies anyone beyond a first name, and it asks search engines not to list it.

## Updating it (owner)
1. Make a fine-grained token: GitHub → Settings → Developer settings → Personal access tokens → Fine-grained tokens. Choose **Only select repositories → Degree-Plan**, set **Contents: Read and write**, and pick an expiration after Dec 18, 2026.
2. Open the page with `#owner` at the end of the address and paste the token. It's stored only on that device.
3. Tap **Start session** when you sit down, and tick items as you finish them. **Settings** sets the session start times and lets you mark a course "not needed" once UMPI confirms it's covered.
