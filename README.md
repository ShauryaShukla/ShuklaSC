# Shaurya Shukla – Portfolio

A plain HTML/CSS site (no build step) for GitHub Pages.

| File | What it is |
| --- | --- |
| `index.html` | Home page |
| `projects.html` | Projects page |
| `about.html` | About Me page |
| `style.css` | Shared styles for all pages (colors are at the top) |

## Editing in VS Code

1. In VS Code, open the Command Palette (`Ctrl+Shift+P`, or `Cmd+Shift+P` on Mac) and run **Git: Clone**.
2. Paste `https://github.com/ShauryaShukla/ShuklaSC` and pick a folder.
3. Open `index.html` and preview it: right-click the file in the Explorer and choose **Reveal in File Explorer / Finder**, then double-click it to open it in your browser. (Optional: install the **Live Server** extension and click **Go Live** to get auto-refresh as you edit.)
4. When you're done, use the **Source Control** tab to commit and push.

### Adding a page

1. Copy `about.html` to a new file, for example `contact.html`.
2. Add a tab for it in the `<ul class="tabs">` list in **every** page.
3. In the new page, move `class="active"` onto its own tab.

## Turning on GitHub Pages

1. On GitHub, open the repo and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at https://shauryashukla.github.io/ShuklaSC/
