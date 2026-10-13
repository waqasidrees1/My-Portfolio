# Waqas Idrees portfolio

Prepared for the public repository `waqasidrees1/My-Portfolio`.
Target URL: https://waqasidrees1.github.io/My-Portfolio/

## Deployment
1. Confirm the connected GitHub account and check whether this repository already exists. Do not overwrite another site.
2. Create the public repository if it does not exist. Upload this folder's contents to its main branch, retaining .github/workflows/pages.yml and the dist directory.
3. In Settings → Pages, choose GitHub Actions as the source.
4. Run the Deploy portfolio to GitHub Pages workflow from Actions if the initial push occurred before Pages was enabled.
5. Confirm the workflow succeeded and check homepage, images, tabs, six-at-a-time pagination, contact draft, robots.txt and sitemap.xml.

If the account or destination URL differs, update the canonical URL, OG URL/image, JSON-LD URLs, robots.txt sitemap URL and sitemap.xml before publishing.
No dependencies or build step. Only dist is published. Source updates to main trigger deployments. GitHub Pages does not collect the enquiry form: it opens an email draft. Analytics events still need a central analytics integration.

The previous hosted site remains available until the GitHub deployment is verified. After migration, choose one primary URL; avoid maintaining two independently indexed copies. Do not delete the previous site before verification.
