# test

Brand directory for the **test** site.

## Preview & Testing

| Environment | URL |
|-------------|-----|
| Preview (post-registration) | https://main--test--nitinkumarbaici.aem.page/ |
| Lighthouse test page | https://main--test--nitinkumarbaici.aem.page/ |
| Production | https://test/ |

> **Note:** The preview URL is available only after Helix Admin site registration
> (manual step — see launch checklist issue).

## Structure

```
brands/test/
├── README.md              # This file
├── tokens.css             # Brand design tokens
├── overrides.js           # Brand block overrides (empty initially)
└── cf-overlay-paths.json  # AEM CF path → URL route mappings
```

## Local Development

```bash
pnpm start:brand test
```

_Scaffolded by BrandBridge — 2026-11-27_
