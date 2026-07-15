# Monargo One website

De officiële marketingwebsite voor Monargo One.

## Structuur

- Meertalige statische website in Nederlands, Frans en Engels
- Volwaardige pagina's voor platform, oplossingen, prijzen, resources, over Monargo, contact en login
- Ontworpen voor Cloudflare Pages
- Cloudflare Pages Function voor het contactformulier

## Lokaal testen

Open `index.html` rechtstreeks in een browser of start een lokale server:

```bash
python -m http.server 8080
```

Open daarna `http://localhost:8080`.

## Cloudflare Pages

Gebruik de repository root als build output. Er is geen buildcommando nodig.

Voor het contactformulier kunnen de volgende omgevingsvariabelen worden ingesteld:

- `RESEND_API_KEY`
- `CONTACT_EMAIL`
- `FROM_EMAIL`

Zonder deze variabelen blijft de website volledig bruikbaar, maar wordt het formulier niet verzonden.
