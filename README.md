<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="eat.me.at landing page" width="880">
  </picture>
</p>

<h1 align="center">eat.me.at</h1>

<p align="center"><strong>Know what you're cooking, and what's in it.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-live-171717?style=flat-square" alt="Status: live">
  <img src="https://img.shields.io/badge/license-source--available-404040?style=flat-square" alt="License: source-available">
  <img src="https://img.shields.io/badge/self--host-supported-525252?style=flat-square" alt="Self-host: supported">
  <img src="https://img.shields.io/badge/part%20of-me.at-737373?style=flat-square" alt="Part of me.at">
</p>

<p align="center">
  <a href="https://eat.me.at">Website</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#built-with">Built with</a>
</p>

Most recipe sites call a dish healthy without showing the working, then leave the shopping to you. I built eat.me.at so every recipe carries a 0-100 Eat Score you can take apart factor by factor, ranks what you can cook from what is already in your kitchen, and turns the rest into one shopping list sorted by aisle. Browsing, reading a score and building a list need no account, and you can run the whole thing on your own server with a license key.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/overview-dark.svg">
    <img src=".github/assets/overview.svg" alt="eat.me.at at a glance: a score you can take apart, cook from what you have, one list for the week, no account to start" width="880">
  </picture>
</p>

## Why eat.me.at

| The usual recipe site | eat.me.at |
| --- | --- |
| A health badge with no working shown | A 0-100 score with each factor's signed contribution and its WHO, USDA or DGA reference |
| A good score hides the problems | Nutrient flags stay visible even when the score is good |
| Recipes you have to shop for | Recipes ranked by what is already in your kitchen |
| One ingredient list per recipe | One list for the week, minus what you own, grouped by aisle |
| Sign up to save anything | A saved pantry or list stays in your browser, with no account |

## Features

- **Eat Score**: every structured recipe gets an explainable 0-100 score showing each factor's signed contribution, the WHO, USDA or DGA reference behind it, a separate data-confidence level, and nutrient flags that stay visible even when the score is good.
- **Cook from what you have**: type what is in your kitchen and get recipes ranked by how much of each you already have, with an avoid list and a coverage threshold. Near misses link their missing items straight into a shopping list.
- **One shopping list for the week**: merge ingredients across several recipes, subtract what you already own, and group the rest by aisle. Filter by allergen, season or substitute, tick items off in the shop, then copy the list or download it as text.
- **Connected recipe pages**: each recipe links to its ingredients, cuisine and techniques, and to dishes with a similar nutrition profile, including healthier alternatives when one exists.
- **Ingredient, cuisine and technique catalogs**: browsable pages with filters, deep-linked from recipes and pantry queries.
- **No account needed to start**: a saved pantry or list stays in your browser. Sign in when you have a license key to activate.
- **Self-hostable**: deploy the Next.js app anywhere Node runs. License keys are verified on your own server against the product's public key, with a grace window if validation lapses.

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow.svg" alt="How eat.me.at works: pantry, match, score, list, shop" width="880">
  </picture>
</p>

You tell eat what is in your kitchen, and it ranks recipes by how much of each one you already have, honoring your avoid list and coverage threshold. Every recipe shows its Eat Score with the working laid out, so you can see which factors helped and which hurt. Whatever you are missing is merged across recipes into one list grouped by aisle, ready to tick off, copy or download.

## Screenshots

<table>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/recipes--miso-butter-salmon-dark.png"><img src=".github/assets/recipes--miso-butter-salmon.png" alt="Miso butter salmon recipe page"></picture><br><sub>A recipe page: structured details and the Eat Score breakdown.</sub></td>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/recipes--smash-burgers-dark.png"><img src=".github/assets/recipes--smash-burgers.png" alt="Smash burgers recipe page"></picture><br><sub>A second recipe: the same score breakdown on a different dish.</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/pantry-dark.png"><img src=".github/assets/pantry.png" alt="Pantry"></picture><br><sub>Pantry: recipes ranked by what you already have on hand.</sub></td>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/shopping-dark.png"><img src=".github/assets/shopping.png" alt="Shopping list"></picture><br><sub>Shopping list: ingredients merged across recipes and grouped by aisle.</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/cuisines-dark.png"><img src=".github/assets/cuisines.png" alt="Cuisines"></picture><br><sub>Cuisines: browse recipes that share a cuisine.</sub></td>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/pricing-dark.png"><img src=".github/assets/pricing.png" alt="Pricing"></picture><br><sub>Pricing: self-host, get a key, activate.</sub></td>
  </tr>
</table>

## Built with

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-19-171717?style=flat-square&logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TypeScript-5-262626?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-404040?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4">
  <img src="https://img.shields.io/badge/Drizzle-Postgres-525252?style=flat-square&logo=drizzle&logoColor=white" alt="Drizzle ORM and Postgres">
  <img src="https://img.shields.io/badge/MDX-recipes-737373?style=flat-square&logo=mdx&logoColor=white" alt="MDX recipe content">
</p>

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- MDX recipe content collection
- oRPC with TanStack Query
- Drizzle ORM with Postgres
- Better Auth
- next-intl
- Signed license keys with offline verification

## Part of the me.at family

eat.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

Source-available. See [LICENSE](LICENSE).
