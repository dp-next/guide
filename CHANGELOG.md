---
toc-depth: 2
---

# Changelog {.unnumbered}

Since we follow [Conventional
Commits](https://decisions.seedcase-project.org/why-conventional-commits/),
we're able to automatically create formal "releases" of the website based on our
commit messages. Releases in the context of websites are simply snapshots in
time of the website content. We use
[Cocogitto](https://decisions.seedcase-project.org/why-semantic-release-with-cocogitto/)
to be able to automatically create these releases, which uses
[SemVar](https://semverdoc.org) as the version numbering scheme, and
[git-cliff](https://decisions.seedcase-project.org/why-changelog-with-git-cliff/)
to generate the changelog based on the commit messages.

Because releases are created based on commit messages, a new release is created
quite often---sometimes several times in a day. This also means that any
individual release will not have many changes within it. Below is a list of the
releases we've made so far, along with what was changed within each release.

Commits from bots, like `dependabot` or `pre-commit-ci`, are not included in the
changelog.

## [0.6.0](https://github.com/dp-next/guide/compare/0.5.0..0.6.0) - 2026-09-21

### ✨ Features

- Move publishing content from other repo
  [#18](https://github.com/dp-next/guide/pull/18) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([39a1a9a](https://github.com/dp-next/guide/commit/39a1a9a25da7ef49e1f2fa648b7ee03e8ccb4ce8))
- Add a practicalities section [#20](https://github.com/dp-next/guide/pull/20)
  by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([2d1b93d](https://github.com/dp-next/guide/commit/2d1b93d3bfc1190fee2cb4e7007c0d78efc2a9c1))

### ♻️ Refactor

- Clarify that WP protocol is made with template-website
  [#21](https://github.com/dp-next/guide/pull/21) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([090d07f](https://github.com/dp-next/guide/commit/090d07fa09662da86d0ee8e255f5b98bf3ba291b))

### 💄 Styling

- Update Quarto theme [#19](https://github.com/dp-next/guide/pull/19) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([ef62456](https://github.com/dp-next/guide/commit/ef624561d6dfa21fc95f3d39ebf6ea5038f5bcca))

## [0.5.0](https://github.com/dp-next/guide/compare/0.4.0..0.5.0) - 2026-09-19

### ✨ Features

- Add protocol writing section [#16](https://github.com/dp-next/guide/pull/16)
  by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([0da6734](https://github.com/dp-next/guide/commit/0da6734fe2c7b79133ecd9527e67c68fab9e8e90))

## [0.4.0](https://github.com/dp-next/guide/compare/0.3.0..0.4.0) - 2026-09-19

### ✨ Features

- Move over project management doc
  [#14](https://github.com/dp-next/guide/pull/14) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([31cd09e](https://github.com/dp-next/guide/commit/31cd09e37dd29e35d45ce18538f42ec6ec1a0f72))

## [0.3.0](https://github.com/dp-next/guide/compare/0.2.0..0.3.0) - 2026-09-19

### ✨ Features

- Move meetings chapter over from wp1-ros
  [#12](https://github.com/dp-next/guide/pull/12) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([a9b3827](https://github.com/dp-next/guide/commit/a9b38272333c1e623da5e9ac9b307a0aca225566))

### 👷 CI/CD

- Comment out broken Quarto render check (for now)
  [#5](https://github.com/dp-next/guide/pull/5) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([a1ad7d0](https://github.com/dp-next/guide/commit/a1ad7d0993704ca6e766271fce9207a8e46140b3))

### ❤️ New contributors

- `@pre-commit-ci[bot]` started making automated contributions

- `@dependabot[bot]` started making automated contributions

## [0.2.0](https://github.com/dp-next/guide/compare/0.1.1..0.2.0) - 2026-08-30

### ✨ Features

- Move authorships section over from `wp1-ros`
  [#4](https://github.com/dp-next/guide/pull/4) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([ce029c1](https://github.com/dp-next/guide/commit/ce029c1209979649ee097333ca11e87e4421af64))

### 💄 Styling

- Don't number appendices [#1](https://github.com/dp-next/guide/pull/1) by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([e876d30](https://github.com/dp-next/guide/commit/e876d3098b5338b73fb19f89d7daefaf9d7a4253))

## [0.1.1](https://github.com/dp-next/guide/compare/0.1.0..0.1.1) - 2026-08-30

### 🐛 Fixes

- Remove `.` before `filename` in code chunks by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([116392c](https://github.com/dp-next/guide/commit/116392c0157e444a79a7198c34a061440a6dc688))

### 👷 CI/CD

- Fix malformed workflow by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([278fce3](https://github.com/dp-next/guide/commit/278fce3f11c45eaa3b3f3be06b9620101ac417c8))

## 0.1.0 - 2026-08-30

### ✨ Features

- Add initial Quarto config file and index files by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([1b3dcea](https://github.com/dp-next/guide/commit/1b3dcea0a77337f61bfd93f9b44f3fa0cf50491e))
- Move over section on starting a project by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([e7c19e6](https://github.com/dp-next/guide/commit/e7c19e637cb3544eedcb4660f179ec031eef811a))
- Move "roles" chapter into this guide by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([29b4021](https://github.com/dp-next/guide/commit/29b4021b3608d4d89ce9e8d866c8542c7f1ad5cd))
- Move and update the DST setup guide by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([d5e8640](https://github.com/dp-next/guide/commit/d5e864053b1f3eb8404da7ce32d06885068b97b8))

### 🐛 Fixes

- Add link to Turing Way website by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([a5f2e85](https://github.com/dp-next/guide/commit/a5f2e85f792475239c1252380e6e0ca0df52962b))

### ♻️ Refactor

- Rename to `overview` from `general` by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([1a71f31](https://github.com/dp-next/guide/commit/1a71f318ddf06b273a5140be4b0836c837e61e79))

### 📝 Documentation

- Minor edits to community health files by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([41f4afd](https://github.com/dp-next/guide/commit/41f4afd1b9ab273d818419c8088c2c42b831ad4f))

### 💄 Styling

- Add DP-Next Quarto theme by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([fb45ae0](https://github.com/dp-next/guide/commit/fb45ae05d49b9d8b9410a137c4ae41cc82bfc7d0))

### 👩‍💻 Miscellaneous

- Start of guide repo by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([8feebcc](https://github.com/dp-next/guide/commit/8feebccfce0c0aab3db3668a7d8fd47fe073b8b1))
- Switch to use `dp-next-theme` in justfile by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([06fce32](https://github.com/dp-next/guide/commit/06fce32811c7eb0eec3d2ceacac2ebe398d78cb1))
- Update and run pre-commit hooks by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([f937cf2](https://github.com/dp-next/guide/commit/f937cf2f154917e61110298ca9556f5f6877d50b))
- Exclude `_book/` and `_extensions/` from TODO listing by
  [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([ae8107a](https://github.com/dp-next/guide/commit/ae8107a80ea3ce1153290e1a11050c6e41869172))
- Ignore Quarto `*_files/` by [`@lwjohnst86`](https://github.com/lwjohnst86)
  ([102e2ed](https://github.com/dp-next/guide/commit/102e2ed1d5ce2231e31c0bd94a7faf4b63cee31e))

### ❤️ New contributors

- `@github-actions[bot]` started making automated contributions

- [`@lwjohnst86`](https://github.com/lwjohnst86) made their first contribution
