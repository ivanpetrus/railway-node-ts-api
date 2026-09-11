# railway-node-ts-api

Minimal Node/TypeScript Express API that listens on `process.env.PORT` and exposes `GET /health`.

Companion repo for the Dev.to post: [Deploy a Node/TypeScript API to Railway in 15 minutes](https://dev.to/ivanpetrus/deploy-a-nodetypescript-api-to-railway-in-15-minutes-with-a-worker-friendly-setup-5gb9).

## Local

```bash
npm install
npm run dev
curl http://localhost:3000/health
```

## Railway

1. New Project → Deploy from GitHub → pick this repo
2. Build: `npm run build`
3. Start: `npm run start`
4. Open the public URL + `/health`

Deploy with Railway (affiliate link — I may earn a commission at no extra cost to you): https://railway.com?referralCode=Bmv7KL&utm_source=github&utm_medium=readme&utm_campaign=railway_deploy_15m
