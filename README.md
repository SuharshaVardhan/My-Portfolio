# My Portfolio

Personal DevOps portfolio for Suharsha Vardhan.

## Stack
- HTML and CSS
- GitHub Actions for validation and deployments
- Vercel for hosting

## Local preview
Open `index.html` in a browser.

## CI/CD configuration
Create a Vercel project and set these GitHub Actions repository secrets:
- `VERCEL_TOKEN`
- `VERCEL_ORG_ID`
- `VERCEL_PROJECT_ID`

Pushes to `master` deploy to production; pull requests deploy to preview environments after validation.
