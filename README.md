# FitScore: public pages

Static pages required for the App Store submission of FitScore, served by GitHub Pages
from the `main` branch root.

| Page | URL | Used for |
|------|-----|----------|
| `index.html` | https://quentin-lauret.github.io/mark/ | Marketing URL |
| `support.html` | https://quentin-lauret.github.io/mark/support.html | Support URL (required) |
| `privacy.html` | https://quentin-lauret.github.io/mark/privacy.html | Privacy Policy URL (required), in-app `PRIVACY_POLICY_URL` |
| `terms.html` | https://quentin-lauret.github.io/mark/terms.html | Terms of Use (EULA), in-app `TERMS_URL`, App Store description |

## Edit and preview

Plain HTML + `style.css`, no build step.

```sh
python3 -m http.server 8080   # then open http://localhost:8080
```

Push to `main` to publish. Update the "Last updated" date when the Privacy Policy or Terms change.
