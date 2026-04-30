# Hacker/Leaker-Themed Static Website Template

Hi guys, this was my first project, so it may be simple, rough around the edges, and contain mistakes. It is kept here mainly for historical purposes, as a record of my early learning process and progress as a developer.

A retro, hacker-style static website template inspired by early web aesthetics: dark backgrounds, neon typography, animated visuals, simple navigation, and archive-style listing pages.

> **Important:** This template is intended for fictional, artistic, educational, cybersecurity-awareness, or media-design projects only. Do not use it to publish stolen data, leaked credentials, private databases, doxxing material, malware, phishing pages, or any content that violates laws, platform rules, or the privacy of real people.

## Overview

This project is a simple static HTML template for building a dark, underground-style website layout. It includes a homepage, FAQ page, submission/contact-style page, robots configuration, and favicon.

The original structure uses placeholder copy such as `YOUR SITE NAME`, archive links, FAQ text, and submission instructions. Replace all placeholders before publishing.

## Project Structure

```text
.
├── index.html      # Main landing page
├── faq.html        # FAQ / about page
├── send.html       # Submission or contact information page
├── robots.txt      # Search engine crawling instructions
├── favicon.ico     # Browser favicon
└── README.md       # Project documentation
```

## Pages

### `index.html`

Main page of the template. It includes:

- Site title placeholder
- FAQ navigation link
- Animated visual element
- Archive-style link list
- Dark hacker-inspired styling
- Favicon reference

Use this page as the public-facing landing page for your fictional archive, cyberpunk project, ARG, CTF challenge, security-awareness campaign, or themed landing page.

### `faq.html`

FAQ and about page. It includes:

- Site title placeholder
- About section
- FAQ placeholder copy
- Link to the submission/contact page
- Matching visual style

Use this page to explain the fictional premise, rules, project scope, credits, or legal/ethical boundaries.

### `send.html`

Submission/contact-style page. It includes:

- Site title placeholder
- Contact or submission placeholder
- Project description area
- Animated visual element
- Matching hacker-style design

For safe use, this page should be adapted as a contact page, tip submission form for lawful reporting, CTF flag submission page, or fictional narrative element. Do not use it to request or collect stolen data.

### `robots.txt`

The included `robots.txt` file currently allows crawling:

```txt
User-agent: *
Disallow:
```

It also includes a note indicating that the file can be deleted if indexing is desired. In practice, this file does **not** block indexing. If you want to block search engines, update it to:

```txt
User-agent: *
Disallow: /
```

Search engines may still index URLs from external links, so use proper access controls when privacy matters. Robots files are not security. They are polite suggestions to crawlers. Very polite. Criminally optimistic.

## Recommended Safe Use Cases

This template works well for:

- Cybersecurity awareness campaigns
- Capture The Flag challenge pages
- Fictional hacker group websites
- Alternate reality games
- Cyberpunk-themed portfolios
- Dark web aesthetic mockups
- Security training simulations
- Journalism or documentary-style landing pages using fictional data
- Red-team exercise storytelling environments, without real-world credential exposure

## What Not to Use This For

Do not use this template to:

- Publish stolen credentials or password lists
- Distribute private databases
- Share doxxing material
- Host malware, droppers, phishing kits, or exploit payloads
- Encourage unauthorized access
- Collect leaked archives from third parties
- Impersonate real organizations or threat groups

A theme is design. A felony is not a feature.

## Customization

Before deploying, update the following placeholders:

- `YOUR SITE NAME`
- `SITE NAME`
- `YOUR FAQ HERE`
- `archive link here`
- `Leaked archive name`
- `your own site's faq link`
- `link to send.html`
- Contact/submission placeholder text in `send.html`

Recommended edits:

1. Replace legacy HTML tags with modern semantic HTML.
2. Move inline styles into a dedicated CSS file.
3. Remove deprecated elements such as `<font>`, `<marquee>`, `<embed>`, and invalid nested HTML structures.
4. Replace third-party hotlinked GIFs and background images with local assets.
5. Remove any external frames or suspicious remote resources.
6. Add responsive layout rules for mobile screens.
7. Add an explicit legal and ethical disclaimer.
8. Use HTTPS when deployed.

## Security Notes

The current HTML contains external resources and legacy embed/frame patterns. Review and clean them before publishing.

Recommended security improvements:

- Remove remote frames and embeds unless absolutely necessary.
- Avoid loading assets from unknown third-party domains.
- Add a Content Security Policy if hosted publicly.
- Keep all downloadable files fictional, sanitized, or legally authorized.
- Do not include real personal data, credentials, tokens, or private records.
- Use static hosting with minimal attack surface.

Example security header configuration:

```http
Content-Security-Policy: default-src 'self'; img-src 'self' https:; script-src 'self'; style-src 'self' 'unsafe-inline'; object-src 'none'; frame-ancestors 'none'; base-uri 'self';
X-Content-Type-Options: nosniff
Referrer-Policy: no-referrer
Permissions-Policy: geolocation=(), microphone=(), camera=()
```

## Local Preview

Because this is a static website, you can preview it locally by opening `index.html` in a browser.

For a simple local server, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This project can be hosted on any static hosting provider, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any standard web server

Basic deployment checklist:

1. Replace all placeholders.
2. Clean unsafe or unnecessary external resources.
3. Confirm all links work.
4. Add your own favicon and assets.
5. Validate the HTML.
6. Review legal and ethical language.
7. Deploy as a static site.

## Suggested Improvements

Future versions could include:

- `assets/` folder for local images, fonts, and icons
- `style.css` for maintainable styling
- `script.js` for optional visual effects
- Responsive layout
- Accessible color contrast
- Safer content policy
- Fictional archive cards instead of raw links
- Markdown-driven content system
- CTF challenge mode

## License

No license is currently provided. Add a license before distributing or publishing this template.

Recommended options:

- MIT License for permissive open-source use
- Apache 2.0 for permissive use with patent language
- Proprietary license if this is for private/internal use only

## Disclaimer

This project is provided as a visual/static website template. The author and contributors are not responsible for illegal, unethical, or harmful use. Users are responsible for complying with all applicable laws, privacy rights, platform policies, and security standards.
