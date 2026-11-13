# Hi, I'm Theuns

I build websites and apps from Gqeberha, South Africa. I run **[Free Rein Development](https://freerein.dev)**, a
one-person studio that makes sites and apps people own and run themselves. I also build and teach in **P3xA**, a
gold price-action mentorship, and make **[Next Entry](https://nextentry.app)**, a trading journal app.

Most of my work lives in private repositories: client work, and paid course material that students agree to keep
confidential. So you won't find the code here. Each project below links to a page that shows what it does, how it's
built and what made it hard.

---

## P3xA Learn · [learn.p3xa.trade](https://learn.p3xa.trade)

<p align="center"><img src="https://raw.githubusercontent.com/tjpienaar/p3xa-learn-showcase/main/images/p3xa-learn-hero.gif" alt="P3xA Learn: a swing points rep drawn and marked on a phone" width="300"></p>

The student portal for the P3xA mentorship: lessons, daily chart practice on real gold price data, a mastery path, a
private notebook and a free public course, plus the tools the mentor and staff run it with.

- **For:** students on their phones, and the team that teaches and marks them.
- **Stack:** Astro 7 on Cloudflare Workers, D1, KV, Better Auth with Discord sign-in, TradingView Lightweight Charts,
  Playwright.
- **Complexity:** server-side marking with a rule engine that works out each chart's answer from the candles; access
  by Discord roles, groups, fees and a free tier on one request path; about 1,900 unit tests and browser tests at
  phone and desktop width, with an automated check that no page sends one student another's data.

**[Read the full write-up →](https://github.com/tjpienaar/p3xa-learn-showcase)**

## Next Entry · [nextentry.app](https://nextentry.app)

<p align="center"><img src="https://raw.githubusercontent.com/tjpienaar/next-entry-showcase/main/images/next-entry-checkin.gif" alt="Next Entry: the check-in and logging a trade" width="300"></p>

A trading journal that steps in before the next bad trade: a checklist and a short check-in before you enter, quick
logging, then guardrails and honest stats after. Free during its beta on iPhone and Android, with a web demo.

- **For:** traders working on discipline and psychology, first for the P3xA community.
- **Stack:** Expo and React Native with Expo Router and TypeScript, SQLite on the phone.
- **Complexity:** one codebase for iPhone, Android and the web; offline, with no account, so all data stays on the
  phone, with file backup and restore to a new phone; risk in R or cash, partials, breakeven and several accounts in
  one entry.

**[More about Next Entry →](https://github.com/tjpienaar/next-entry-showcase)**

## re-Genesis companion · [web demo](https://tjpienaar.github.io/re-genesis-preview/)

<p align="center"><img src="https://raw.githubusercontent.com/tjpienaar/re-genesis-showcase/main/images/re-genesis-today.gif" alt="re-Genesis: the morning ritual and the quilt" width="300"></p>

The daily companion app for the book *re-Genesis* by Theunis Pienaar: a morning ritual, a belief for the day,
practices that open chapter by chapter, an evening journal and a patchwork quilt that fills in one patch a day.

- **For:** readers who want to live the book day by day.
- **Stack:** Expo and React Native with TypeScript, on-device storage, EAS Build; the web demo on GitHub Pages.
- **Complexity:** one codebase for iPhone, Android and the web, with no backend; content that follows the reader's
  chapter; saved days protected through cold starts and a rebrand; a web demo seeded with ten weeks of history.

**[More about re-Genesis →](https://github.com/tjpienaar/re-genesis-showcase)**

## Free Rein Development · [freerein.dev](https://freerein.dev)

<p align="center"><img src="https://raw.githubusercontent.com/tjpienaar/free-rein-showcase/main/images/free-rein-home.png" alt="freerein.dev at desktop and phone width"></p>

My studio. Websites and apps for businesses, built so the domain, hosting and content are in the client's name and
they can edit the site without me. Once-off pricing, ready-made designs, and moves off Wix with redirects meant to
protect search rankings.

- **For:** small businesses that want a site they own.
- **Stack:** Astro and plain CSS on Cloudflare: nothing extra for visitors to download, and code any developer can
  take over.
- **Complexity:** each custom site's look built from the business's own brand, then handed over so the client runs it.

**[More about Free Rein →](https://github.com/tjpienaar/free-rein-showcase)**

---

## More work

- **[Free Rein ready-made designs](https://freerein.dev/designs/)**: six working sites, each shown with a made-up
  business, from a one-page workshop site with a WhatsApp quote form to a nursery shop with click-and-collect
  ordering. Every one has a live demo.
- **[p3xa.trade](https://p3xa.trade)**: P3xA's one-page website: the free Discord and YouTube, the mentorship, and
  Next Entry. Hand-built HTML and CSS with trimmed web fonts and responsive screenshots.
- **[theunispienaar.com](https://theunispienaar.com)**: the author website for Theunis Pienaar and *re-Genesis*,
  with the book, the companion app, a journal and contact. Its journal also feeds the posts inside the app.
- **Oxley English website** (in progress): the new site for my family's online English school for students in
  China.

---

## How I work

- I start from who will use it and the few things they must be able to do, then build those well.
- Phone first, and checked at phone and desktop width.
- Tests and backups before anything goes live, so I can change things quickly without breaking them.
- I build with AI coding tools, with tests and reviews on everything before it ships. That's how one person keeps
  this pace.

**Tools I use most:** TypeScript, Astro, Cloudflare (Workers, Pages, D1, KV), Expo and React Native, SQLite,
Playwright.

**Get in touch:** [freerein.dev](https://freerein.dev)
