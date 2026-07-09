# BNETCORE Solutions — Roadmap

Future improvements for the site, not yet implemented. Nothing here is live.

## High Priority

- **Portfolio** — populate the hidden Portfolio section (`index.html`) with real client projects, then remove the comment wrapper to re-enable it.
- **Contact form** — the Contact section is currently click-to-call/email cards only (no form). Add a proper inquiry form (with spam protection) if phone/email alone isn't generating enough leads.
- **Confirm production domain** — `canonical`/`og:url` currently assume `https://bnetcore.ro/`; update if the real domain differs.
- **Cookie consent** — add a consent banner before adding any analytics/tracking scripts.
- **Accessibility audit** — full manual pass (screen reader, keyboard-only navigation, color contrast in both themes) beyond the checks done during this migration.

## Medium Priority

- **Case studies** — detailed write-ups once real client projects exist.
- **Testimonials** — client quotes/reviews section.
- **Pricing** — public pricing or package comparison page.
- **Company stats / social proof** — a numbers section (projects delivered, uptime, clients) once real figures exist. (The Atom template's placeholder "12 projects / 3 awards" stats were intentionally removed rather than reused.)
- **Blog CMS** — the Blog section currently uses the template's static sample article; replace with real posts and a lightweight CMS or static-site generator once there's content to publish.
- **Social media integration** — add real social links to the header/footer once BNETCORE accounts exist (the template's placeholder social icons were removed rather than linked to nowhere).
- **OG / social share image** — add a real `assets/img/social.jpg` and reference it via `og:image` (removed the template's generic placeholder).
- **SEO improvements** — structured data (LocalBusiness schema), sitemap.xml, robots.txt.
- **Analytics** — add privacy-respecting analytics (e.g. Plausible/Fathom) after cookie consent is in place.

## Low Priority

- **Multilingual support** — extend the current EN/RO client-side toggle to real i18n routing if more languages are needed.
- **Search functionality** — only relevant once the Blog has enough real posts.
- **Client portal** — authenticated area for clients to see hosting/backup status.
- **Knowledge Base / FAQ** — self-serve support content.
- **Service pages** — dedicated landing page per service (web design, hosting, photography) instead of the single-page sections.
- **Team page** — once there's more than one person to introduce.
- **Careers** — once/if BNETCORE is hiring.
- **RSS feed** — once the Blog has real, recurring content.
- **Newsletter integration** — no newsletter signup currently exists on the site; add one (with real ESP integration) if there's a reason to collect subscribers.
- **Performance optimization** — revisit whether the Tailwind CDN build is still the right tradeoff once the site has enough traffic to justify a real build/purge step.



