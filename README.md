# Junteng Liu — LJT-Homepage

Personal academic website for Junteng Liu, forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

## Content

- `_pages/about.md`: homepage with personal details, education, research interests, research experience, honors, publications, and contact information.
- `_pages/publications.html`: the Publications page.
- `_publications/`: the six publication records, also rendered on the homepage from the same source files.
- `_config.yml` and `_data/navigation.yml`: personal settings and section navigation.

The recorded publication years are used without inventing exact publication dates. No portrait or details absent from memory have been supplied.

## Build and publishing

The site uses Jekyll. The GitHub Actions workflow in `.github/workflows/jekyll.yml` builds the site and verifies both publication lists, personal details, contact links, local navigation, and the page inventory.

Project-site path: `/LJT-Homepage`.

GitHub Pages must be enabled by the repository owner under **Settings → Pages → Build and deployment → Source → GitHub Actions**. Automatic activation was rejected by GitHub for the workflow token. Once that setting is enabled, run the deployment workflow again. The build and validation run independently of deployment.

Configured site address after activation: https://spallaselvylt934293.github.io/LJT-Homepage/

Theme attribution and license are retained from Academic Pages.
