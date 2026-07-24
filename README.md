# Navnegenerator

En lille generator, der parrer et dansk fornavn med en dansk arbejdsbeskrivelse –
fx **Per Murer**, **Lars Tandlæge** eller **Lone Brugsuddeler**.

Tryk på knappen for at få et nyt navn. Der er kun navnet og en knap på siden.

## Sådan virker det

- Alt ligger i `index.html` (ingen afhængigheder, ingen build).
- Fornavnene er et kurateret udvalg af **kun danske/nordiske navne** – ingen
  internationalt klingende navne.
- Arbejdsbeskrivelserne er klassiske danske stillingsbetegnelser og fag.

## GitHub Pages

Siden udgives automatisk via GitHub Actions (`.github/workflows/pages.yml`).

Første gang skal Pages slås til: **Settings → Pages → Build and deployment →
Source: GitHub Actions**. Herefter deployes siden ved hvert push til branchen.
