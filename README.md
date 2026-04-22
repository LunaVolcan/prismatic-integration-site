# Prismatic Integration

Website for [Prismatic Integration](https://prismaticintegration.com) — a queer- and trans-led somatic care practice in Albuquerque, NM offering therapeutic massage, breathwork, and hypnotherapy with a trauma-informed, sliding-scale model.

## Stack

Static single-page site — plain HTML, CSS, and vanilla JS. No build step, no dependencies.

## Structure

```
index.html       Main page
images/          Favicons, practitioner photos, social preview thumbnail
sitemap.xml      For Google Search Console submission
robots.txt       Crawler directives
```

## Deployment

Hosted on Netlify. Push to `main` and it deploys automatically.

The contact form uses [Netlify Forms](https://docs.netlify.com/forms/setup/) — submissions appear in the Netlify dashboard under **Forms**. To set up email notifications: Netlify dashboard → Site → Forms → contact → Form notifications.

## SEO

- `<meta name="description">` and canonical URL in `<head>`
- JSON-LD `HealthAndBeautyBusiness` structured data
- `sitemap.xml` — submit to [Google Search Console](https://search.google.com/search-console) after deploy
- `robots.txt` pointing to the sitemap
