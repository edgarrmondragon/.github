# Renovate Configurations

## Examples

### Singer Tap

A Singer tap that uses uv for package management:

```json5
{
  // https://docs.renovatebot.com/configuration-options/#extends
  "extends": [
    // https://github.com/edgarrmondragon/.github/blob/main/renovate/singer.json5
    "edgarrmondragon/.github//renovate/singer.json5",

    // https://github.com/edgarrmondragon/.github/blob/main/renovate/uv.json5
    "edgarrmondragon/.github//renovate/uv.json5",
  ],
}
```
