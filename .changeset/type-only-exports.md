---
"eslint-plugin-import-x": patch
---

Fix false duplicate-export reports for type-only wildcard and named exports in `import-x/export`, while retaining duplicate type, explicit named, and default export checks. Fixes [#414](https://github.com/un-ts/eslint-plugin-import-x/issues/414).

Keep string-literal export names distinct from internal namespace tags and preserve their full names in duplicate-export diagnostics.
