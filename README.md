# kapp-content

Static pages for the [Kapp](https://github.com/JesperStockenstrand/kapp) app, served by Vercel (as `still-content` does for Still). No build step, no backend.

| Page | Used by |
|---|---|
| `privacy.html` | the app (sign-in step, Settings), App Store and Play listings |
| `terms.html` | the app (sign-in step, Settings, safety notice) |
| `support.html` | the app (Settings), App Store support URL |
| `index.html` | links to the three |

Push to `main` and Vercel deploys. When a policy changes in a way that matters, update the "Last updated" date.
