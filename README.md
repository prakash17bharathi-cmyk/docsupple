# Doctor Supplement Guide

An evidence-based educational resource providing comprehensive information about commonly used nutritional supplements.

## Overview

This website is a static HTML site that provides general educational information about nutritional supplements. It includes detailed information about:

- **What each supplement is** — Origin, composition, and mechanism
- **Common uses** — Primary applications and benefits
- **Who may benefit** — Ideal candidates for supplementation
- **Possible side effects** — Safety considerations and interactions
- **Dosage information** — Typical supplemental doses
- **Dietary sources** — Natural food sources of nutrients

## Supplements Included

1. Magnesium
2. Vitamin D
3. Omega-3 Fatty Acids
4. Creatine
5. Probiotics
6. Psyllium
7. Berberine
8. Zinc
9. Turmeric
10. Ashwagandha

## Technology Stack

- **HTML5** — Clean semantic markup
- **CSS3** — Responsive design
- **No JavaScript, no backend, no database** — Pure static site

## Deployment

This site can be deployed to:

- **GitHub Pages** — Free hosting (site-name.github.io)
- **Vercel** — Free hosting (site-name.vercel.app)
- Any other static hosting service

## File Structure

```
/
├── index.html              (Homepage with supplement grid)
├── about.html              (About this guide)
├── disclaimer.html         (Medical disclaimer)
├── css/
│   └── style.css           (All styling)
└── supplements/
    ├── magnesium.html
    ├── vitamin-d.html
    ├── omega-3.html
    ├── creatine.html
    ├── probiotics.html
    ├── psyllium.html
    ├── berberine.html
    ├── zinc.html
    ├── turmeric.html
    └── ashwagandha.html
```

## Adding New Supplements

To add a new supplement page:

1. Duplicate an existing supplement page (e.g., `magnesium.html`)
2. Update the supplement name and information
3. Save as `supplements/supplement-name.html`
4. Add a new card link on `index.html`
5. Commit and push to GitHub

## Important Legal Notice

**This website provides educational information only** and is not intended to be medical advice. Always consult with a qualified healthcare provider before starting any supplement regimen.

See [disclaimer.html](disclaimer.html) for complete legal information.

## Features

✅ Fully responsive design (mobile, tablet, desktop)  
✅ Clean, professional interface  
✅ Fast loading (no dependencies or third-party scripts)  
✅ SEO-friendly HTML structure  
✅ Easy to maintain and update  
✅ No hosting or maintenance costs  

## Getting Started

1. Clone this repository
2. Open `index.html` in a web browser to preview locally
3. Deploy to GitHub Pages or Vercel for free hosting

## Contributing

To suggest new supplements or improvements, please open an issue or pull request.

## License

Educational content only. For specific license details, see the repository.

---

**Note:** This site provides general educational information based on published research. It is not medical advice and should not replace consultation with qualified healthcare professionals.
