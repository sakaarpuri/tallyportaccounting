# Tallyport Accounting

Static marketing site for Tallyport Accounting.

UK services include bookkeeping, PAYE payroll, VAT, management accounts and year-end tax support. Public pricing is not displayed.

## Files

- `index.html` - main site
- `assets/refinements.css` - responsive layout, card motion and visual refinements
- `logo-options.html` - unindexed comparison page for three proposed vector identities; the live site retains the existing logo until a direction is chosen
- `assets/branding/concepts/` - outlined SVG logo concepts and font licence
- `Aura Code for Tallyport.rtf` - local Aura reference used during design adaptation

## Contact Form

The `consultation` form uses Netlify Forms with required fields and a honeypot. Form detection must be enabled in Netlify. Submissions appear in the site's Forms dashboard; email notifications are configured there separately.

## Visual Direction

Headings use Manrope and body copy uses Source Sans 3. Mustard, deep teal, charcoal and clay colour blocks provide contrast against neutral sections. Logo concepts are kept separate from the production identity.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://127.0.0.1:8000/`.

