---
title: "Project Setup 2021"
date: 2021-10-03T21:25:04+02:00
draft: true
---

## Step 1: Use TypeScript instead

Well, sorry for the lie.

Check out the following `.eslintrc`:

```json
{
  "root": true,
  "parser": "@typescript-eslint/parser",
  "plugins": ["@typescript-eslint", "prettier"],
  "extends": [
    "eslint:recommended",
    "plugin:@typescript-eslint/eslint-recommended",
    "plugin:@typescript-eslint/recommended",
    "prettier"
  ],
  "rules": {
    "prettier/prettier": "error"
  }
}
```
