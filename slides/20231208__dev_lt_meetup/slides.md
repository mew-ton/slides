---
theme: apple-basic
transition: slide-left
title: hacomono LT 会
layout: cover
---

# 2023 年の Frontend

Frontend Enabling LT

<div class="absolute bottom-10">
  <span class="font-700">
    @_mew_ton 2023/12/08
  </span>
</div>


---
layout: intro
---

# 1. Framework

---
layout: iframe
url: https://2022.stateofjs.com/en-US/libraries/front-end-frameworks/
---

---
layout: intro
---

# 2023 の Vue / Nuxt

---
layout: default
---

# Remind

- Vue 3 .. Released 2020/09
- Nuxt 3 .. RC Released 2022/04, Released 2022/11
- ※ Nuxt は Vue を拡張するフレームワーク

## 参考

- hacomono pos .. First Commit 2022/02

実は Nuxt 3 Beta 版の時点で導入検討していた !

---
layout: default
---

# Nuxt の Migrate に苦しめられた年

- Nuxt 3 のリリースが 2年遅れた
- Vue 2 → 3 の破壊的な変更, Nuxt 2 → 3 の破壊的なアーキテクチャの刷新で、二重苦

---
layout: iframe
url: https://vuefes.jp/2023/#timetable
---

---
layout: default
---

# Vue のコミュニティが他へ影響を与えた

- Vue, Nuxt の内部処理やツール郡を他のフレームワークでも使えるようにする動き

## e.g.

- Volar .. Vue の Language Server → Svelte でも利用
- Vite .. Vue / Nuxt の Build Tools → 他の F/W でも広く採用
- Nitro .. Nuxt の server side engine → Angular でも利用

---
layout: intro
---

# 2. DX

---
layout: intro
---

# 速さ = DX

---
layout: default
---

# Rustify

- どれもこれも Rust 製に置き換わる

## e.g.

- webpack → rspack, turbopack <br>
vite も Rust で書き直し予定
- babel → swc
- eslint / prettier → Biome
- Bun v1 released (alternative node, deno)
- Loco .. Ruby on Rails と似た思想の Rust フレームワーク

---
layout: default
---

# Bun

- Node.js の代替となる Rust 製のランタイム
- `npm install` が爆速
- 実行スピードが node, deno に比べて早い
- アイコンがかわいい

---
layout: intro
---

# 3. UX

---
layout: intro
---

# 軽さ = UX

---
layout: default
---

# No JS / Less JS

- JavaScript がなければ、理論上最速 の思想

## e.g.

- (2022) Astro .. SSG / MPA で Zero JS 実現
- (2023) VanJS .. 総重量 1kB 未満の JS フレームワーク

---
layout: default
---

# Less JS on Nuxt

- Nuxt Island .. コンポーネント単位での Server Side Rendering
- Nitro .. Nuxt の server side engine
- その他 .. バージョンアップごとにバンドルサイズが大きく増えないようにしている

