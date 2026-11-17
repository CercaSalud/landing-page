# CercaSalud Landing Page

Static Astro landing page for validating interest in CercaSalud. The page is intentionally not an emergency service and does not activate monitoring or response.

## Local development

Requires Node.js 22.23.4 or newer.

```sh
npm install
npm run dev
```

Create a production build with `npm run build`; preview it with `npm run preview`.

## Interest form activation

The form is disabled by default. A static page cannot receive registrations until an approved submission provider is configured. This project is set up for Netlify Forms, but do not enable public collection until the team has:

- Published and reviewed a privacy notice describing the data controller, purpose, fields, Netlify's processing role, access, retention, and how to exercise deletion rights.
- Published a working contact channel for privacy and deletion requests.
- Confirmed who can access submissions and how long they will be retained.
- Confirmed that the notice and consent language are appropriate for the intended audience and jurisdiction.
- Disclosed the hosting provider's processing of standard request logs in the privacy notice.

Only after those requirements are met, configure these Netlify build environment variables:

```text
PUBLIC_ENABLE_INTEREST_FORM=true
PUBLIC_PRIVACY_APPROVED=true
PUBLIC_PRIVACY_URL=https://your-domain.example/privacy
```

Set `PUBLIC_PRIVACY_APPROVED=true` only after a responsible team member verifies that `PUBLIC_PRIVACY_URL` is the real, published privacy notice and that its content and data practices are approved. This is a deliberate manual safeguard, not an automatic legal review. Without all three settings, no Netlify form is rendered and no registrations are collected through the interest form. The site host may still process standard request logs. Do not collect health details through this form.

## Deployment

The included `netlify.toml` builds the static site to `dist/`. Deploy the `landing/` directory as the Netlify site base directory. Before relying on submissions, confirm Netlify form detection is enabled for the site and complete a test submission in a staging deployment.

## Hero image

The local family image is sourced from Pexels, photo 9385084. Replace it with a project-owned or otherwise approved image before public launch if its representation does not match the audience or brand.