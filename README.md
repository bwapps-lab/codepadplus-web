# CodePad+ Website

Simple static website for CodePad+.

## Before publishing

Replace these placeholders:

- `you@example.com`
- `YOUR_USERNAME/YOUR_REPOSITORY`
- Google Play URL if your final package/listing changes
- Privacy Policy wording if you later add ads, analytics, crash reporting, or network SDKs

## Local preview

```bash
npm install
npm run dev
```

## Deploy to Cloudflare Workers

```bash
npm install
npm run deploy
```

Static files are served from `public/` using `wrangler.jsonc`.

## GitHub

Create a new repository, then:

```bash
git init
git add .
git commit -m "Initial CodePad+ website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

You can then connect the GitHub repository to Cloudflare if you prefer automatic deployments.
