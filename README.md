# Brick Tempo support website

Static English/Turkish support and privacy pages. Publish only this directory in a separate public repository; no app source or credentials are included. No build step or third-party front-end dependency is required.

Do not put app-ads.txt here. This site is served under /bricktempo/, but AdMob only reads https://kadirkiras.github.io/app-ads.txt at the domain root, which needs the separate kadirkiras.github.io user-site repository (the file is prepared in the app project at AppStore/app-ads.txt). Suggested GitHub Pages source: main branch, repository root. Support URL: https://kadirkiras.github.io/bricktempo/ ; privacy URL: https://kadirkiras.github.io/bricktempo/privacy.html (pending publication).

Privacy text checked against App/GameSession.swift and App/InterstitialAds.swift on 2026-10-14, plus Google's iOS SDK data disclosure and GitHub Pages hosting documentation. On 2026-10-24 the advertising paragraph was re-checked against App/Core/AdPacing.swift: interstitials appear only after a run ends, never during a run. Review again if SDKs, ad settings, storage or support handling change.
