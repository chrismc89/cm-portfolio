# Christopher McCourt — AI & Cloud Dev Portfolio

Personal portfolio site. Deployed via AWS Amplify Hosting at [portfolio.cmccourt.net](https://portfolio.cmccourt.net).

## Local Preview

Open `index.html` in a browser — no build step required.

## Deployment

Connected to AWS Amplify. Push to `main` branch to trigger an auto-deploy (~90 seconds).

## Stack

- Static HTML/CSS — no framework, no build step required
- Font Awesome icons (CDN)
- Google Fonts (CDN)
- Hosted at `portfolio.cmccourt.net` via AWS Amplify + Route 53

## Update Workflow

```bash
# Edit index.html, then:
git add .
git commit -m "Update portfolio"
git push
# Amplify auto-deploys in ~90 seconds
```
