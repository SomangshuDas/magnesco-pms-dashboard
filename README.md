# MAGNESCO Production Management System Dashboard

This repository contains the source for the **MAGNESCO Production
Management System Dashboard**, an internal tool used by **Magnesco
Electrical Stamping Pvt. Ltd.** for production monitoring, plus install
redirect pages for the companion Android APKs.

## ⚠️ Important — Public Repository Notice

This repository is public **only because GitHub Pages requires public
repositories for free static hosting**. It is **not published for reuse,
contribution, or distribution**. The content, code, and assets here are
proprietary and intended solely for internal use by Magnesco Electrical
Stamping Pvt. Ltd.

**Do not** copy, fork for reuse, redistribute, or repurpose any part of this
repository. See [LICENSE](./LICENSE) for full terms — in short: all rights
reserved, viewing the source is permitted incidentally as a result of static
hosting, nothing more.

## Project Structure

```
magnesco-pms-dashboard/
├── index.html                          # Dashboard entry point
├── app/                                # Android app download/install redirect pages
│   ├── index.html                      # Install page — Production Management System app
│   └── tv/index.html                   # Install page — Dashboard TV app
├── css/style.css                       # Dashboard stylesheet
├── js/                                 # Dashboard scripts
│   ├── script.js                       # Core dashboard logic
│   ├── config.js                       # Configuration
│   ├── installer.js                    # Install page behaviour
│   └── tv-installer.js                 # TV install page behaviour
└── assets/
    ├── images/                         # Logo and background images
    ├── icons/                          # Favicon
    └── files/                          # Distributable Android APKs
```

## Hosting

The dashboard is a static site intended for hosting on **GitHub Pages** (or
any static host). No build step is required — all pages are plain HTML,
CSS, and vanilla JavaScript.

This is an **internal tool**, not a public-facing product. It is hosted
publicly only due to GitHub Pages' free-hosting requirement; it is not
intended for public discovery or use.

## Distributed Apps

The `app/` directory serves install redirect pages for the companion
Android APKs (`MAGNESCO_Production_Management_System.apk` and
`MAGNESCO_Production_Management_System_Dashboard.apk`) found under
`assets/files/`.

## Copyright

Copyright © 2026 Magnesco Electrical Stamping Pvt. Ltd. All Rights Reserved.

Brand names, logos, and company information for Magnesco Electrical
Stamping Pvt. Ltd. displayed on this dashboard belong to their respective
owner and are used with permission.
