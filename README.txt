ShivTrix Natural Datun - website package
========================================
index.html                      The complete website (HTML + CSS + JS, product photos built in)
404.html                        Friendly "page not found" page
.nojekyll                       Tells GitHub Pages to serve files as they are
.github/workflows/static.yml    GitHub Pages deploy workflow
images/                         Your 7 datun product photos (optional, for reuse)

Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload everything in this folder (keep the .github folder and .nojekyll).
3. Settings > Pages > Build and deployment > Source: GitHub Actions.
4. Push to main (or run the workflow from the Actions tab).
   Site: https://YOUR-USERNAME.github.io/REPO-NAME/

To change prices, products or the WhatsApp number, edit the DATA block near the
bottom of index.html (id="data"). cfg.wa is the WhatsApp number with country code 91,
cfg.delivery is the delivery charge, cfg.cod turns Cash on Delivery on or off.
