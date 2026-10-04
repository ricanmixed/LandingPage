# Patriot House Sober Living — Temporary Landing Page

This is a responsive, single-page "coming soon / contact us" website for Patriot House Sober Living.

## Files
- `index.html` — complete webpage (HTML, CSS, and tiny year script are included in one file).

## Before publishing
Please verify the phone number and email in `index.html`. The page currently uses:
- Phone: 609-525-4506
- Email: info@patriothouseokc.org
- Location wording: MacArthur & Northwest Expressway area, Oklahoma City

The page intentionally does not show a fixed bed count or exact street address, so it won't become outdated or reveal a residential address. Edit those details if you want them public.

## GitHub + Deploy Now workflow
1. Create a new GitHub repository, for example `patriot-house-landing-page`.
2. Upload `index.html` to the repository root (top level, not inside another folder).
3. Commit the change to the default branch.
4. In IONOS Deploy Now, connect the GitHub repository and create a project for a static website.
5. Set the deployment/build configuration to publish the repository root. No build command is needed for this plain HTML site.
6. Connect the domain or subdomain you want to use for the temporary page, then deploy.
7. Open the live URL on a phone and computer to test the layout, phone link, and email link.

If your Deploy Now project asks for a build output directory, use the repository root (`.`) for this static HTML page. The exact labels in the IONOS interface may vary.

## Editing
Open `index.html` in any text editor. Search for the phone number, email, location, or wording you want to change. The layout adapts to mobile screens.

## Notes
- Google Fonts are loaded from Google Fonts; the page still displays with fallback fonts if that service is unavailable.
- This is a static landing page and does not collect or store visitor information.
