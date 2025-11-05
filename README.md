
# Sahara Premium Wear — Static Site

This is a single-file (index.html) site with images. It’s ready for GitHub Pages.

## How to publish (GitHub Pages)
1. Create a **new repository** on GitHub (any name, e.g. `sahara-site`).
2. Upload these files: `index.html`, `prototype.jpg`, `hoodie.jpg`, `pants.jpg`, `README.md`.
3. Go to **Settings → Pages**.
   - **Source**: select **Deploy from a branch**.
   - **Branch**: choose **main** and folder **/** (root). Save.
4. Wait ~30–60 seconds. Your site will appear at:  
   `https://<your-username>.github.io/<repo-name>/`

### Optional (root domain style)
If you name the repository exactly `your-username.github.io`, your site will be at:  
`https://your-username.github.io/`

## Notes
- Everything is static (HTML/CSS/JS). No build tools required.
- Images are referenced by relative paths in the same folder as `index.html`.
- For real checkout, connect Stripe/Shopify later.
