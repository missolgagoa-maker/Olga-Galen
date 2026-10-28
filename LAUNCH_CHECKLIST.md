# Private Launch Checklist — Olga Galen Website

Items that must be supplied or confirmed before public launch.

## Required from Olga

- [x] Preferred business contact email address: alphagaleinc@gmail.com
- [x] Phone: +1 (720) 593-9595
- [ ] Professional portrait photograph (if desired; currently typography-led)
- [ ] LinkedIn profile URL (optional but recommended)
- [ ] Confirmed website domain
- [ ] Final approval of all public copy (especially experience descriptions and metrics framing)
- [ ] Decision on whether company name “Home Alliance” may appear publicly (currently used)
- [ ] Any approved testimonials or references (none currently published)
- [ ] Pricing guidance or minimum engagement size (none published by design)
- [ ] Contact form destination (email service or form provider credentials)
- [ ] Scheduling link if desired (Calendly etc.)

## Technical / legal before go-live

- [ ] Connect real email delivery for the contact form (Resend/Postmark/etc. or Formspree)
- [ ] Set `NEXT_PUBLIC_SITE_URL` environment variable
- [ ] Update `robots.txt` and sitemap base URL with the real domain
- [ ] Draft and publish a Privacy Policy that accurately describes data practices
- [ ] Confirm analytics approach (if any) and disclosure
- [ ] Review accessibility and mobile layout on real devices
- [ ] Run `npm run build` and fix any remaining TypeScript or lint issues
- [ ] Test form submission end-to-end with the chosen delivery method

## Content decisions already made (no action needed unless change desired)

- Tagline retained: “Strategic Thinking. Commercial Execution. Sustainable Growth.” (used in positioning)
- Primary CTA: “Discuss a Project” / “Start a Conversation”
- No fabricated testimonials, logos, case studies, or performance claims
- Organizational metrics framed as context, not personal results
- No pricing published

## Incomplete / deferred features

- Real email delivery for contact form (logging only until configured)
- Professional portrait (none supplied)
- Privacy Policy page (draft needed once data practices are finalized)
- Optional: blog or insights section (not in original scope)
- Optional: structured data / JSON-LD for Person or ProfessionalService (can be added once domain is live)
