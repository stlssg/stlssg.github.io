# Personal portfolio

A restrained, responsive academic website built with plain HTML, CSS, and
JavaScript. It includes About, Publications, and Service pages, plus an
unlisted recruiting-information page. It is ready for GitHub Pages and needs
no build step.

## Customize it

Open `index.html` and replace:

- The biography, research interests, news, and opening notice
- `your.email@university.edu` and the office address
- The recruiting details in `recruiting.html`

Open `publications.html` and replace the sample publications, authors, venues,
and resource links. You can change the color palette at the top of `styles.css`.

## Preview locally

Open `index.html` directly in a browser, or start a local server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish on GitHub Pages

1. Create a GitHub repository named `YOUR-USERNAME.github.io`.
2. In this folder, run:

   ```bash
   git init
   git add .
   git commit -m "Create personal portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```

3. In the repository on GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. Your site will appear at `https://YOUR-USERNAME.github.io/`.

For a regular repository name (for example `portfolio`), the site URL becomes
`https://YOUR-USERNAME.github.io/portfolio/`.
