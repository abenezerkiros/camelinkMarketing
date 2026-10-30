# CAMELINK marketing website
A single-page Next.js App Router website. Blue/white CAMELINK identity, responsive layouts, scroll reveals, animated route, accessible interactive journey tabs, FAQ accordions and native dialog with role-specific next steps. Reduced-motion support included.

## Run
Use Node.js 22 or newer. Run `npm install`, then `npm run dev`. Open http://localhost:3000.

## Deploy
Run `npm run build`. The static website is generated in `out/`. Host this directory on any static host, or import the project into Vercel with the Next.js preset. This page requires no Firebase or Mapbox credentials. Its journey illustration is not a live tracker.

Copy `.env.example` to `.env.local` and set the real customer app URL and operations phone number when available; rebuild after changing these public settings. Until configured, Get started honestly explains that pilot access/contact details are forthcoming. No form submits data and no marketing leads are stored. No invented phone numbers, testimonials, delivery statistics or app-store links are included.

Logo: supplied CAMELINK brand asset. Road photograph: Unsplash, https://images.unsplash.com/photo-1519003722824-194d4455a60c (illustrative, not a claim about CAMELINK fleet or geography). Fonts: Google Fonts DM Sans and Manrope with local system fallbacks. Self-host fonts if desired.

The .openai directory configures the private Sites preview; it can be omitted on other hosting platforms.
