# dorm.shop workshop website

Website for *A unifying framework for dormancy across scales*, May 11–13, 2027.

The site header reads "DormShop". The homepage has no call-to-action buttons and its second paragraph uses plain text. The Workshop and People pages include the ASM address and both co-organizers, respectively.

## Upload to GitHub

Add the **contents** of this package (including the folders beginning with `_`) to the root of `dorm-shop/dorm-shop.github.io`. Keep the existing `LICENSE`; replace the starter `README.md`. GitHub Pages is already configured to publish from `main` and `/(root)`.

GitHub's **Add file → Upload files** supports dragging the **uncompressed folder's contents** into the upload area. Check that `_config.yml`, `index.md`, `_data/navigation.yml`, `_pages/*.md`, and `assets/images/dormancy-across-life.png` have the indicated paths before committing. A ZIP file uploaded as one file will not become a website.

The site uses the Minimal Mistakes remote theme and the GitHub Pages Jekyll build. If the deployment fails, inspect **Actions** for the exact build error.

## Editing

- `index.md`: homepage copy and banner
- `_pages/workshop.md`: logistics
- `_pages/program.md`: goals, agenda, and future outcomes
- `_pages/people.md`: organizers and participants
- `_data/navigation.yml`: navigation links
- `_config.yml`: site identity and theme

The proposal contained earlier tentative dates and a different city. The website uses the confirmed May 11–13, 2027 dates and ASM headquarters address supplied by the organizers. The banner reproduces a figure credited to Lennon et al. (2021); confirm reuse terms before distributing the public site widely.

To use `dorm.shop` as the website address later, register/control that domain and configure it under repository **Settings → Pages → Custom domain**. Update `_config.yml` `url` at the same time.
