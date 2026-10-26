# Daily City Planner website

Public landing page: https://truizlop.github.io/daily-city-planner-site/

Static HTML/CSS, published by GitHub Pages from `main` at the repository root.
Run locally with `python3 -m http.server 8767`.

The September 2026 refresh uses actual screenshots from the game's verified
September 17 build, local licensed fonts, responsive layouts, reduced-motion
support, and an ad/purchase privacy policy at `privacy.html`.

The app is available on the App Store: https://apps.apple.com/app/id6789138152
The hero and footer link to the public listing, verified on September 22, 2026.
Safari can also show the native Smart App Banner.

AdMob seller authorization is also published at the domain root:
https://truizlop.github.io/app-ads.txt
The project copy is supplied for portability; AdMob crawls the domain root.

The official App Store badge is stored unchanged from Apple:
https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg

The launch hero shows a completed native puzzle board and an approved result.
The approval capture uses illustrative demo progress: a 14-day streak, matching
best and total, and seven solved days. Captured with StoreCampaignCaptureTests
on September 22, 2026; the app source and saved progress are restored afterward.

## German localization (October 2026)

The German landing page is at `de/`, with `de/support.html`, `de/privacy.html`
and `de/terms.html`. English pages remain at the root. Each page offers an
explicit language link and reciprocal canonical/hreflang metadata; no browser
language redirect is used. The privacy translation preserves the published
September 22, 2026 policy, including Firebase Analytics and Crashlytics.
The terms pages retain the app’s existing Apple Standard EULA.

The official German App Store badge is stored unchanged from Apple:
https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/de-de

German screenshots are native captures from the German 2.4 localization build,
captured on October 24, 2026 from the October 8 puzzle: `native.03-city.png`,
`native.04-approved.png` and `native.02-clues.png` in the app screenshot source
archive. The approval capture shows a one-day streak; its native text is unchanged.
The German social preview uses the same authentic game screenshot as the hero.
Publish by pushing reviewed changes to `main`; GitHub Pages uses the repository
root and its existing Pages build and deployment workflow.

## Italian localization (October 2026)

Italian pages are at `it/`, `it/support.html`, `it/privacy.html`, and `it/terms.html`.
They preserve the existing layout, policy and Apple Standard EULA destination.
The native screenshots come from the Italian 2.5 build. The official Italian
App Store badge is bundled unchanged from Apple’s marketing tools.
Language links are explicit and reciprocal; there are no automatic redirects.
