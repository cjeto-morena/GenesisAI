#  Rovek Deploy

**zero-config deployment tool for static and SSR sites**

![Node](https://img.shields.io/badge/node-%3E%3D18-green)
![CI/CD](https://img.shields.io/badge/ci%2Fcd-ready-blue)

## usage

```bash
npx rovek-deploy
```

automatically detects your framework (Next.js, Astro, Nuxt, Vite) and pushes to edge CDN.

## init project

```bash
rovek init mysite
```

creates `.rovek/config.json`:

```json
{
  "name": "mysite",
  "region": "ap-sg",
  "env": {
    "NODE_ENV": "production"
  }
}
```

## deploy

```bash
rovek deploy
```

output:

```
✓ detected nextjs
✓ building... (24s)
✓ deploying... (8s)
Deployed → https://mysite.rovek.app
```

## integrations

* GitHub Actions ([actions.rovek.app](https://actions.rovek.app))
* GitLab CI ([gitlab.rovek.app](https://gitlab.rovek.app))
* Cloudflare DNS Sync ([dns.rovek.app](https://dns.rovek.app))

## plans

| tier  | bandwidth | domains | price  |
| ----- | --------- | ------- | ------ |
| hobby | 100GB     | 1       | free   |
| pro   | 1TB       | 10      | $10/mo |
| team  | ∞         | ∞       | $25/mo |

MIT © [rovek.app](https://rovek.app)

# Touch update: 1760686863
