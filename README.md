```markdown
# GHOREO – Host Trust Landing Page

A responsive landing page for GHOREO, a platform for hosts in Dhaka to manage bookings, resolve disputes, and receive payouts.

## Features

- Responsive design for mobile, tablet, and desktop
- Security labels and verification badges
- Brand colors (teal #003C32, light gray #F7F7F7)
- Sticky call-to-action button linked to Google Form

## Optimizations

- **SEO Meta Tags**: Includes title, description, keywords, author, and geo tags for Dhaka to improve local search visibility.
- **Open Graph (OG) Image**: Custom 1200×630 banner (`Og-image.jpg`) for rich social media previews on Facebook, LinkedIn, Twitter, and WhatsApp.
- **Twitter Cards**: Configured for large image summary.
- **Favicon Set**: Complete icon package for all devices (desktop, iOS, Android) including manifest file.
- **Canonical URL**: Prevents duplicate content issues.
- **Theme Color**: Browser UI color set to brand teal.

## File Structure

```

/
├── index.html
├── site.webmanifest
├── Og-image.jpg
├── favicon-32x32.png
├── favicon-16x16.png
├── favicon.ico
├── apple-touch-icon.png
├── android-chrome-192x192.png
└── android-chrome-512x512.png

```

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/rezajoy/Ghoreo-host-trust.git
```

1. Edit index.html to update:
   · Text content (intro, features, corporate info)
   · Google Form link in the CTA button
2. Replace Og-image.jpg with your own 1200×630 social image.
3. Open index.html in a browser to preview.

Deployment

GitHub Pages

· Push to repository
· Go to Settings > Pages
· Under "Branch", select main and folder / (root)
· Click Save

Netlify

· Drag the project folder to Netlify Drop

Custom Domain

Update your domain's DNS records to point to your hosting provider. The canonical URL in the HTML is already set to https://ghoreo.com.

Verification

· OG Image: PostEverywhere OG Checker
· Facebook Sharing: Sharing Debugger
· Favicon: Open browser DevTools (F12) → Network tab, reload the page, and check that all icon files load (status 200).

License

MIT

```