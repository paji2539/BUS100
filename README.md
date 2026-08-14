# Business Basics — Chapter 1 lecture

A single-file, interactive 50-minute lecture companion for BUS 100, built from
the Chapter 1 "Business Basics" content (Pearson, *Better Business* 7e) and
instructor lecture highlights.

## What's inside

- 12 sections covering objectives 1.1–1.4, paced to 50 minutes (shown per-section
  in the left-hand "receipt" rail)
- Click-to-sort activities (goods vs. services, for-profit vs. nonprofit, B2C/B2B/C2C)
- Flip cards for the factors of production
- A click-matching game for the "life skills = business skills" comparison
- Built-in countdown timers for each in-class activity
- Keyboard navigation (← / →), mobile-responsive layout, reduced-motion support

No build step, no dependencies beyond a Google Fonts link — just one HTML file.

## Hosting on GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Upload `index.html` to the repository root (drag-and-drop on github.com works fine).
3. Go to **Settings → Pages**.
4. Under **Source**, select the branch (usually `main`) and folder `/ (root)`, then **Save**.
5. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`
   within a minute or two.

## Using it in class

Open the published link on the classroom display, click **Begin class** to start
the clock, and use the **Next / Prev** buttons (or arrow keys) to move through
sections at your own pace. The left rail shows every stop with its time budget —
click any item to jump there directly if you want to skip around.

## Editing content

Everything lives in `index.html` — section content is plain HTML inside labeled
`<section class="slide" data-idx="N">` blocks, so you can edit text directly.
The `SECTIONS` array near the top of the `<script>` tag controls the rail
labels and time budgets shown in the sidebar.
