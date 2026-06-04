MOSCATELLI Studio PWA — 2026-06-03-l

Files included:
- index.html
- manifest.webmanifest
- sw.js
- icons/ favicon and PWA icon set

Deployment notes:
1. Upload the contents of this ZIP to the GitHub Pages /hub/ repository or folder.
2. Keep index.html, manifest.webmanifest, sw.js, and icons/ at the same level.
3. Open https://gianmoska-prog.github.io/hub/ after deployment.
4. If an older version appears, clear site data once or open in an incognito window, then reload.

Icon notes:
- The favicon/app icons were generated from the supplied Moscatelli monogram image.
- Favicon and standard app icons include rounded corners.
- Maskable icons include safe-area padding for phone home-screen masks.

Patch M: removed the default mobile/PWA blue tap highlight rectangle from triangle links and bumped the service-worker cache.

Patch N: mobile-only visual refinement for the Studio Index PWA. Desktop styles above 920px were left untouched.

Patch O: added return-from-external recovery so closing a PWA browser sheet cannot leave Studio stuck in fade-out.
