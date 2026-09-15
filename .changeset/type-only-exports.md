---
"eslint-plugin-import-x": patch
---

Fix false duplicate-export reports for type-only wildcard and named exports in `import-x/export`, while retaining duplicate type, explicit named, and default export checks. Fixes [#414](https://github.com/un-ts/eslint-plugin-import-x/issues/414).
