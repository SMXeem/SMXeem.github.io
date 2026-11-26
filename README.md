# Portfolio site

Plain HTML and CSS, with no build step. The files:

- `index.html`: all the page content
- `styles.css`: the design, always in the light theme
- `assets/Sayed_Al_Zawad_Resume.pdf`: the resume behind the download buttons. Replace this file when the resume changes.

## Preview locally

```powershell
python -m http.server 5510 --directory portfolio
```

Then open http://localhost:5510

## Put it online (free)

**GitHub Pages** (gives a `smxeem.github.io` style address)
1. Create a public repo named `<your-github-username>.github.io`.
2. Upload the contents of this folder (`index.html`, `styles.css` and `assets/`).
3. Open the repo's Settings, then Pages, and set the source to the `main` branch, root folder.

**Netlify Drop** (fastest)
1. Go to https://app.netlify.com/drop
2. Drag this `portfolio` folder onto the page.

**Vercel**: import the repo and choose "Other" as the framework. No build command is needed.

Once it's live, add the link to your LinkedIn (Contact info, then Website), your BDJobs profile and your resume header.
