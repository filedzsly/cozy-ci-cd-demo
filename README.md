# cozy-ci-cd-demo

Simple Node.js CI demo with GitHub Actions and GitHub Pages deployment.

## Local commands

- `npm test`

## GitHub Actions

- CI workflow: runs tests on pushes and pull requests to `main`
- CD workflow: deploys the static site in `site/` to GitHub Pages on pushes to `main`

## GitHub Pages setup

In the GitHub repository settings:

1. Open `Settings > Pages`
2. Set `Source` to `GitHub Actions`
3. Push to `main` to trigger deployment
