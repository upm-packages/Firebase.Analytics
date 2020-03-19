# Firebase Analytics

## Installation

```bash
upm add package com.google.firebase.analytics
```

Note: `upm` command is provided by [this repository](https://github.com/upm-packages/upm-cli).

You can also edit `Packages/manifest.json` directly.

```jsonc
{
  "dependencies": {
    // (snip)
    "com.google.firebase.analytics": "[latest version]", 
    // (snip)
  },
  "scopedRegistries": [
    {
      "name": "Unofficial Unity Package Manager Registry",
      "url": "https://upm-packages.dev",
      "scopes": [
        "com.google"
      ]
    }
  ]
}
```

## Usages

Read https://firebase.google.com/docs/unity/setup
