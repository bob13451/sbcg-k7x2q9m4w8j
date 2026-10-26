GEWY BUILDS PROFIT TRACKER
==========================

Put it online with GitHub Pages (free), then install it on your phone.

1. On github.com, tap "+" > New repository. Name it e.g. gewy-builds. Set it to Public. Create it.
2. Upload ALL the files from this folder (index.html, manifest.webmanifest, sw.js,
   and the three icon-*.png files). index.html must sit in the top level of the
   repository, not inside another folder.
3. Go to the repository's Settings > Pages. Under "Build and deployment" choose
   Source: "Deploy from a branch", Branch: main, Folder: / (root). Save.
4. Wait about a minute. Your link will be:
   https://YOUR-USERNAME.github.io/gewy-builds/
5. Open that link in Chrome on your phone, then use the menu (three dots) >
   "Install app" or "Add to Home screen".

Notes
- Your sales are saved on the phone, in the browser that has the app. They do not
  sync between devices.
- Use Export > "Back up everything" now and then. "Restore from backup" loads that
  file back in.
- GitHub Pages is public, so anyone with the link can open the (empty) app. Your
  sales are NOT on GitHub, they stay on your phone.
- If you change index.html later, also change CACHE = 'gewy-builds-v1' in sw.js to
  a new name (for example v2) so phones pick up the update.
