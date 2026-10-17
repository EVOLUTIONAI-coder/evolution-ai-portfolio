Evolution AI — portfolio site
================================

Live site source for the Evolution AI portfolio.

index.html is the whole site: a single self-contained page (no build step,
no framework, no dependencies beyond Google Fonts).

Media
-----
The video, poster and storyboard stills are hosted on the workspace CDN and
are referenced from index.html via its <base href>. They are deliberately not
stored in this repository.

Deploying
---------
This repo can be served as-is by GitHub Pages:
  Settings > Pages > Source: "Deploy from a branch" > main / (root)

Rendering caveat
----------------
If you serve this through a service that returns the file as
application/octet-stream, browsers will download it instead of rendering it.
GitHub Pages and most static hosts serve .html correctly.
