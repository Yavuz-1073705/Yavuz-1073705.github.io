# yavuz-1073705.github.io

Persoonlijke website van Yavuz Atilgan. Gewone HTML en CSS, gebouwd met [Astro](https://astro.build) en gehost op GitHub Pages.

## Lokaal draaien

```bash
npm install
npm run dev
```

Daarna naar http://localhost:4321.

## Bestanden

- `src/pages/index.astro`: de pagina (HTML)
- `src/styles/global.css`: de opmaak (CSS)
- `public/afbeeldingen/`: plaatjes

Geen JavaScript nodig. De lengte van een skill-balk pas je aan met `style="width: 88%"` in `index.astro`.
- `.github/workflows/deploy.yml`: zet de site automatisch online na een push naar `main`

## Online zetten

1. Maak op GitHub een repository `Yavuz-1073705.github.io`.
2. Push dit project naar de `main` branch.
3. Ga naar Settings > Pages > Source en kies **GitHub Actions**.
