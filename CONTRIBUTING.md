# Contributing to the Kiva Design System Reference

This repository is the canonical token reference for the Kiva product platform. To keep the reference authoritative and consistent, change-approval is intentionally narrow.

## Roles

| Role | Who | Permissions |
|---|---|---|
| Owner | Lin Zhao | Sole administrative owner of the `kiva-design-system` organization. Final decision on scope, structure, and publication. |
| Editor | Lin Zhao, Biju Baek | Members of the `@kiva-design-system/editors` team. Write access to this repository. Authorized to merge pull requests. |
| Member | All other org members | Read access. May open issues and submit pull requests, but cannot merge. |

## Who can merge a pull request

Only members of the `@kiva-design-system/editors` team can merge to `main`. Every pull request must be reviewed and approved by an editor before merging, regardless of who opened it.

## How to propose a change

1. **Open an issue first** for any change that affects token values, naming, or the structure of the reference. This gives editors a chance to align on scope before code is written.
2. **For typo or copy fixes**, a pull request without a prior issue is acceptable.
3. **Fork or branch**, make the change, and open a pull request against `main`.
4. **Describe the source of truth**: link the Figma file, the `@kiva/kv-tokens` version, or the spec that justifies the change.
5. An editor will review, request changes if needed, and merge.

## What is in scope

- Token value corrections that bring the reference in line with the Figma variable library or the `@kiva/kv-tokens` package.
- New panels or sections that document an existing part of the design system.
- Accessibility, copy, and clarity improvements to the reference itself.

## What is out of scope

- Adding tokens or values that do not exist in the source-of-truth Figma library.
- Visual redesign of the reference site without prior editorial approval.
- Republishing, repackaging, or forking this reference for external distribution. See `LICENSE`.

## Questions

For interpretation of intent, scope, or editorial decisions, contact Lin Zhao or Biju Baek.
