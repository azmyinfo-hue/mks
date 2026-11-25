# MKS Group website

Static one-page site (HTML, CSS and JavaScript in `index.html`). No build step.

## Publish on GitHub Pages
1. Create a repository, for example `mks-group-website`.
2. Upload everything in this folder (keep the `assets` folder next to `index.html`).
3. In the repository go to Settings > Pages, choose "Deploy from a branch", select `main` and `/ (root)`, then Save.
4. Your site appears at `https://<username>.github.io/<repository>/` within a minute or two.

## Custom domain (optional)
Add a file named `CNAME` containing `www.mksgroupco.com`, then point the domain's DNS to GitHub Pages.

## Editing
- Text and project cards: `index.html` (the `P` array in the script holds the project cards).
- Colors and fonts: the `:root` variables at the top of the `<style>` block.
- Logos are transparent PNGs in `assets/`.
- The 3D skyline loads three.js from a CDN. If it cannot load, the page still works with a plain dark hero.

## Adding project photos
Put JPG photos (about 1600 px wide, under 400 KB each) in the matching folder, numbered from 1:
`assets/projects/<project-folder>/1.jpg`, `2.jpg`, `3.jpg` and so on (up to 10). The first photo becomes the card image and all of them open in a viewer.
Folders: tower-hawalli, villas-sabah-al-ahmad, office-capital, school-jahra, retail-salmiya, hospital-hawalli, factory-shuwaikh, hotel-fahaheel, kaifan-villa, shamiya-estate, formwork-structures, turnkey-fitout.

For the interiors and finishing gallery (below the day and night scene) use `assets/gallery/1.jpg` to `8.jpg`. Until photos are added, project cards show an architectural line drawing and the gallery stays hidden.
