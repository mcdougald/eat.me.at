<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="eat.me.at landing page" width="880">
  </picture>
</p>

# eat.me.at

Know what you're cooking, and what's in it.

Eat is a nutrition-aware cooking app. It gives every recipe a 0-100 score you can take apart, ranks what you can cook from what is already in your kitchen, and turns the rest into one shopping list sorted by aisle. Browsing, reading a score, and building a list need no account, and you can run the whole thing on your own server with a license key.

## Features

- **Eat Score**: every structured recipe gets an explainable 0-100 score showing each factor's signed contribution, the WHO, USDA or DGA reference behind it, a separate data-confidence level, and nutrient flags that stay visible even when the score is good.
- **Cook from what you have**: type what is in your kitchen and get recipes ranked by how much of each you already have, with an avoid list and a coverage threshold. Near misses link their missing items straight into a shopping list.
- **One shopping list for the week**: merge ingredients across several recipes, subtract what you already own, and group the rest by aisle. Filter by allergen, season or substitute, tick items off in the shop, then copy the list or download it as text.
- **Connected recipe pages**: each recipe links to its ingredients, cuisine and techniques, and to dishes with a similar nutrition profile, including healthier alternatives when one exists.
- **Ingredient, cuisine and technique catalogs**: browsable pages with filters, deep-linked from recipes and pantry queries.
- **No account needed to start**: a saved pantry or list stays in your browser. Sign in when you have a license key to activate.
- **Self-hostable**: deploy the Next.js app anywhere Node runs. License keys are checked offline against the product's public key, so the app never calls home to unlock itself.

## Screenshots

<table>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/recipes--miso-butter-salmon-dark.png"><img src=".github/assets/recipes--miso-butter-salmon.png" alt="Recipe page"></picture><br><sub>Recipe: structured details and the Eat Score breakdown</sub></td>
    <td width="50%"><img src=".github/assets/pantry.png" alt="Pantry"><br><sub>Pantry: see what you can make from ingredients on hand</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/cuisines-dark.png"><img src=".github/assets/cuisines.png" alt="Cuisines"></picture><br><sub>Cuisines: browse recipes that share a cuisine</sub></td>
    <td width="50%"><img src=".github/assets/pricing.png" alt="Pricing"><br><sub>Pricing: self-host, get a key, activate</sub></td>
  </tr>
</table>

## Built with

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

See [LICENSE](LICENSE).
