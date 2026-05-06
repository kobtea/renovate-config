# renovate-config

Renovate config presets for personal use.

## Usage

For personal repos:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>kobtea/renovate-config"]
}
```

For other users who want only the common preset:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>kobtea/renovate-config:common"]
}
```

## Validation

```bash
pnpm install
pnpm run validate
```
