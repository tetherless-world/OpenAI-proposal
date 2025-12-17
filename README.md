# OpenAI-proposal

This repository hosts a GitHub Pages site.

## GitHub Pages

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### Setup

This repository is configured with:
- **index.html**: Main page for the site
- **GitHub Actions workflow**: `.github/workflows/pages.yml` - Automatically deploys the site to GitHub Pages
- **Permissions**: The workflow has appropriate permissions to deploy to GitHub Pages

### Viewing the Site

Once deployed, the site will be available at: `https://tetherless-world.github.io/OpenAI-proposal/`

### Manual Deployment

You can manually trigger the deployment workflow from the Actions tab in the GitHub repository.

### Repository Settings Required

To enable GitHub Pages for this repository:
1. Go to repository Settings → Pages
2. Under "Build and deployment", select "Source" as "GitHub Actions"
3. The site will be automatically deployed on the next push to `main` or via manual workflow trigger