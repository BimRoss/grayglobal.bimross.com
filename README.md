# Gray Global — marketing site

Static marketing site for Gray Global, a boutique strategic development and investment advisory firm led by David Glossop (Dubai, UAE).

Built from the firm's capability statement. Hand-written HTML and CSS, no build step, no framework. Six pages plus three insight articles.

## Structure

```
public/
  index.html                       Home
  services.html                    Services
  experience.html                  Experience (asset classes + selected programmes)
  insights.html                    Insights index
  insight-feasibility-reset.html   Article
  insight-owner-side-gap.html      Article
  insight-cost-escalation.html     Article
  about.html                       About / leadership
  contact.html                     Contact + enquiry form
  css/style.css                    Design system
  img/                             Hero + section photography (AI-generated), favicon
  CNAME                            Pages custom domain
```

## Local preview

```bash
cd public && python3 -m http.server 8899
# open http://localhost:8899/
```

## Deploy

GitHub Pages via `.github/workflows/pages.yml` — pushes to `main` publish `public/` automatically.

## PLACEHOLDER content — must be replaced before this goes to real clients

The following are invented for the preview and are **not real**:

- Email `david.glossop@grayglobalpartners.com`
- Phone `+971 4 401 7600`
- LinkedIn `linkedin.com/in/davidglossop`
- Office `Gate Avenue, DIFC, Dubai`
- The "DG" portrait block is a monogram placeholder — swap in a real headshot.
- Section/hero photography is AI-generated. Replace with licensed or real project imagery before any commercial use.

The contact form has **no backend** yet. It shows a confirmation on submit but does not send anything. Wire it to an email service (Formspree, a serverless function, or a mailto) before launch.

## Facts in the copy

Project figures on the Experience page were researched and deliberately kept to verifiable, evergreen numbers (e.g. Roy Hill's 344 km rail, North East Link's budget movement). Total-cost figures for NEOM and QCLNG were intentionally left out because the public numbers are contested. Confirm any specific client engagement details with David before implying a named role.
