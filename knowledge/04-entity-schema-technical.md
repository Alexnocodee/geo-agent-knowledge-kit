# Entity, Schema, And Technical Signals

## Entity Clarity

The agent should check whether the brand is easy to identify as an entity.

Look for:

- Consistent brand name
- Clear category
- Headquarters or market where relevant
- Founder/team information when useful
- Product/service definition
- Audience definition
- SameAs links to trusted profiles
- Contact and organization details
- Consistent descriptions across the web

## Homepage Entity Block

The homepage should make these obvious in the first viewport or early HTML:

- Brand name
- Category
- Who it serves
- What problem it solves
- Key proof
- Primary call to action

Example:

```text
Acme is an AI visibility platform for ecommerce brands. It tracks how products are recommended in ChatGPT, Perplexity, and Gemini, then shows which content and citations improve recommendation share.
```

## Schema Checklist

Use schema only when it accurately represents real page content.

Common schema types:

- Organization
- WebSite
- WebPage
- BreadcrumbList
- Product or Service
- FAQPage
- Article
- HowTo
- Review or AggregateRating only when valid and compliant
- SoftwareApplication for software products

## GEO-Friendly Page Structure

Use:

- One clear H1
- Descriptive H2/H3 headings
- Short direct answer blocks
- Bullets and tables
- Definitions
- Steps
- Comparison tables
- Evidence blocks
- FAQ sections
- Last updated date when freshness matters
- Author or editorial details when trust matters

## Machine-Readable Claims

A claim is GEO-friendly when it is:

- Specific
- Attributable
- Verifiable
- Not exaggerated
- Close to supporting evidence

Weak:

```text
We are the best AI visibility agency.
```

Better:

```text
We help B2B SaaS and ecommerce teams map buyer prompts, build AI-citable content, implement schema, and track AI-referred conversions in GA4.
```

## Technical Cautions

- Do not hide important content in scripts that crawlers cannot render.
- Do not rely only on images for key claims.
- Do not create fake schema.
- Do not spam prompts into hidden text.
- Do not assume `llms.txt` is a silver bullet.

