# Toddler meals

Public recipe site for Chanel’s ~20-month-old. Each recipe page includes **schema.org Recipe JSON-LD** so [Umami](https://www.umami.recipes) can import ingredients + steps from a URL.

## Live site

After GitHub Pages is enabled: **https://chanelluuhai.github.io/toddler-meals/**

## Weekly workflow

1. Saturday: Nibble asks what was tried and what he thought.
2. Chanel replies → Nibble drafts ~3 meals (grocery list + recipe).
3. Chanel **approves** which recipes to publish.
4. Nibble updates this site with those recipes and shares the links.
5. Chanel pastes each link into Umami → grocery list.

Nothing is published or pushed to Umami until Chanel says so.

## Sample recipes

- [Soft scrambled eggs + avocado toast fingers](recipes/soft-scrambled-eggs-avocado.html)
- [Cheese quesadilla wedges](recipes/cheese-quesadilla-wedges.html)
- [Mini turkey meatball bowls](recipes/mini-turkey-meatball-bowls.html)

## Adding a week

1. Add HTML under `recipes/` (include Recipe JSON-LD).
2. Link them from `index.html` and optionally `weeks/YYYY-Www.html`.
3. Push to `main` — Pages deploys via Actions.
