# Psychiatric Provider (demo)

Prototype therapist/psychiatrist directory for Alex McCabe / Blank Slate Therapy feedback.

- Single-page app (`index.html`)
- Sample data only — forms save in the browser, nothing is sent
- Brand name is one line near the top of the script: `const BRAND = "Psychiatric Provider"`

## Local

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
```

## Note

All clinicians and practices are fictional.

## Update (Oct 29, 2026)
- Texas launch market (Indiana was removed the same day): Frisco, Southlake, McKinney, Lewisville, Dallas, Fort Worth, Austin, Houston, San Antonio (sample data).
- State + city search/filters, browse-by-city, state-scoped specialty pages.
- Professional blue/teal directory look; all differentiators retained.

## Update (Nov 12, 2026)
- Sample opening/confirmed dates are shifted relative to today, so no "next opening" shows a past date.
- Home quick-match labels are readable (they were white on white); no duplicate "Texas" option.
- Sticky page bar sits below the 988 banner on phones; one Home button per page; favicon.
