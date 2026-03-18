# NM Template - Roofing

Proper roofing website template with placeholder-based content injection.

**Created from:** Google Drive Roofing Website Template (original)  
**Type:** PLACEHOLDER_* pattern based  
**Trade:** Roofing / Roofer

## Placeholders Used

| Placeholder | Description | Example |
|-------------|-------------|---------|
| PLACEHOLDER_BUSINESS_NAME | Full business name | "JWY Roofing and Building" |
| PLACEHOLDER_SHORT_NAME | Short name/logo text | "JWY" |
| PLACEHOLDER_PHONE | Phone number | "020 8226 4403" |
| PLACEHOLDER_WHATSAPP | WhatsApp number (usually same as phone) | "020 8226 4403" |
| PLACEHOLDER_EMAIL | Business email | "info@jwyroofing.co.uk" |
| PLACEHOLDER_AREA | Service area | "South East London" |
| PLACEHOLDER_REGION | Region | "London" |
| PLACEHOLDER_POSTCODE | Postcode | "SE25 6RP" |
| PLACEHOLDER_STREET | Street address | "20 Claret Gardens" |
| PLACEHOLDER_WEBSITE_URL | Website URL | "https://jwy-roofing.co.uk" |
| PLACEHOLDER_RATING | Google rating | "5" |
| PLACEHOLDER_REVIEW_COUNT | Number of reviews | "117" |
| PLACEHOLDER_SERVICES | Comma-separated services | "Emergency Repairs, Flat Roofs..." |
| PLACEHOLDER_REVIEW_1 | First review | "Great service..." |
| PLACEHOLDER_REVIEW_2 | Second review | "Professional..." |
| PLACEHOLDER_REVIEW_3 | Third review | "Highly recommend..." |

## Template Structure

```
src/
├── sections/
│   ├── Hero.tsx          # Hero section with CTA
│   ├── Services.tsx      # Services grid
│   ├── About.tsx         # About section
│   ├── Testimonials.tsx  # Reviews
│   ├── Contact.tsx       # Contact form
│   ├── Coverage.tsx      # Coverage areas
│   ├── Process.tsx       # Work process
│   ├── Projects.tsx      # Project gallery
│   ├── FAQ.tsx           # FAQ accordion
│   └── Footer.tsx        # Footer
├── components/ui/        # shadcn/ui components
└── App.tsx              # Main app

public/
└── images/
    ├── hero-roofer.jpg
    ├── roof-repair.jpg
    ├── flat-roof.jpg
    ├── new-roof.jpg
    ├── guttering.jpg
    ├── emergency-repair.jpg
    └── chimney-repair.jpg
```

## Images Included

All roofing-specific images:
- Hero: Professional roofer on roof
- Services: Roof repair, flat roof, guttering, chimney repair, emergency repair

## Usage

1. Clone this template
2. Replace all PLACEHOLDER_* values with business data
3. Update images if needed
4. Build and deploy

## Differences from Plumbing Template

- Roofing-specific imagery
- Roofing services (not plumbing)
- Roofer-focused hero section
- Roof repair testimonials
- No Gas Safe / boiler references
