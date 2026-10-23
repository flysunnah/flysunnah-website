# Fly Sunnah — Free Static Website

Mobile-first static landing page for Fly Sunnah. Source files: `index.html`, `styles.css`, `script.js`, and `favicon.svg`.

## What this site does
- Presents flight-ticket assistance, tourist-visa documentation support, work-permit guidance, and Umrah planning.
- Provides direct WhatsApp, phone, email, and Facebook links.
- Includes responsive navigation, metadata, and TravelAgency JSON-LD.
- Includes a visa disclaimer. It does not promise visa/work-permit approval.

## Important scope limits
This is a static information and contact website. It does not include flight inventory/GDS integration, online booking, payments, customer accounts, visa application submission, case tracking, or a customer database. Do not add secrets or customer documents to this repository.

## Before public launch
1. Review all service descriptions and confirm they match the services actually available.
2. Confirm phone numbers, email, and Facebook page.
3. The final hosting URL is intentionally not hard-coded in canonical/structured URL fields. Once a real deployment URL exists, update metadata/JSON-LD and verify it.
4. Check the live page, all contact links, mobile layout, and browser console after deployment.
5. Do not connect `flysunnah.com` or change its DNS until the owner explicitly decides to use that domain.

## Free hosting
Cloudflare Pages is a suitable candidate for this static site. In Cloudflare Dashboard, create a Pages project and connect this GitHub repository (`flysunnah/flysunnah-website`) using the Git integration, or use Direct Upload. For a plain static site, set the build command to empty/no build and the output directory to the repository root. Select a free `*.pages.dev` subdomain if available. The exact project URL is only confirmed after Cloudflare creates it.

## Verification status
Source files are committed to GitHub. This does not mean the site is deployed. HTTPS, public URL, browser behavior, and live links must be checked after hosting setup.
