# Xan Abuser. + Papyrus

Simple GitHub Pages host for the **Xan Abuser.** theme and **Papyrus** font pack.

## Live page

After you enable GitHub Pages, the site will be at:

```
https://<your-username>.github.io/<repo-name>/
```

The page has one-click **Copy Theme JSON** and **Copy Font JSON** buttons, plus direct raw links.

## Files

| File | What it is |
|------|------------|
| `xan-abuser.json` | Full theme (spec 2) — colors + fonts |
| `papyrus.json` | Font pack (spec 1) |
| `index.html` | GitHub Pages UI with copy buttons |
| `README.md` | This file |

## How to put this on GitHub (web UI)

1. Go to [github.com/new](https://github.com/new)
2. Create a new repository (public is easiest for Pages)
3. On the repo page click **Add file → Upload files**
4. Drag these four files in:
   - `xan-abuser.json`
   - `papyrus.json`
   - `index.html`
   - `README.md`
5. Commit the changes

### Enable GitHub Pages

1. Repo → **Settings** → **Pages** (left sidebar)
2. Under **Source** choose **Deploy from a branch**
3. Branch: `main` (or `master`) → folder: `/ (root)`
4. Save

Wait ~30–60 seconds, then open:

```
https://<your-username>.github.io/<repo-name>/
```

## Direct raw links (after Pages is live)

Replace the placeholders:

```
https://<your-username>.github.io/<repo-name>/xan-abuser.json
https://<your-username>.github.io/<repo-name>/papyrus.json
```

You can also use the raw.githubusercontent.com URLs if you prefer:

```
https://raw.githubusercontent.com/<your-username>/<repo-name>/main/xan-abuser.json
https://raw.githubusercontent.com/<your-username>/<repo-name>/main/papyrus.json
```

## Usage in clients

- Paste / import the theme JSON into whatever client supports the format (spec 2).
- Paste / import the Papyrus font JSON the same way (spec 1).

---

Author of the theme: **Risk/Kuai** (`1539564445037240420`)
