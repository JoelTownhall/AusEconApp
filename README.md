# AusEcon

A dashboard for following the Australian economy:

- **Calendar**: upcoming RBA and ABS releases plus key international dates (`public/data/calendar.json`)
- **Reports**: summaries of research newsletters (`public/data/reports.json`)
- **Chart pack**: key macro charts (`public/data/charts.json`)

It is currently a static mock-up with sample data, served by Cloudflare Workers (static assets).

## Develop

```sh
npm install
npm run dev      # http://localhost:8787
```

## Deploy

```sh
npx wrangler login   # or set CLOUDFLARE_API_TOKEN
npm run deploy       # publishes to https://auseconapp.<your-subdomain>.workers.dev
```
