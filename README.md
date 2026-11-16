# Visitsly — Marketing Website

Static website for Visitsly (AI visit booking for real estate, India & UAE). No build step.

```
Website/
├── index.html          Home (hero, features, ROI calculator, pricing, FAQ)
├── demo.html           Interactive live demo
├── contact.html        Contact form (opens WhatsApp)
├── privacy.html        Privacy Policy
├── terms.html          Terms of Service
├── robots.txt
├── sitemap.xml
└── assets/
    └── css/saas.css    Shared SaaS design layer (loaded by every page)
```

Run locally: `python3 -m http.server 8000` and open http://localhost:8000
"Book free demo" buttons link to https://visitsly.com/login
