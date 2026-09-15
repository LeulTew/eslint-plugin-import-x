---
"eslint-plugin-import-x": patch
---

Fix false duplicate-export reports for type-only wildcard and named exports in `import-x/export`, while retaining duplicate checks within each export namespace. Fixes [#414](https://github.com/un-ts/eslint-plugin-import-x/issues/414).
