---
'@scalar/workspace-store': minor
'@scalar/schemas': minor
'@scalar/types': minor
'@scalar/api-reference': minor
---

feat(api-reference): `textColor` on `x-badges`

Each badge accepts an optional `textColor`, in the same formats as `color`. When it is omitted the text color is derived from `color` as before, which reads poorly on mid-tone backgrounds.
