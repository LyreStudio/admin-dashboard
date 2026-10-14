# Validation — 2026-10-14

Windows x64, Node 24.19.0, Playwright Chromium. Upstream archive SHA-256 and actual MIT license verified before preparation. No upstream package/build scripts were executed.

- Local server serves all 20 public assets. Private source/config, .git, .env, .lyre, encoded traversal, malformed requests and writes are denied; HEAD has no body. `npm test` passes.
- Real Chromium loads all 11 HTML pages at 1440×1000 and 390×844 without horizontal document overflow, script errors or failed resource requests. Sample forms announce that no data is sent. Responsive menus open. Initial dashboard resize measurement was taken before Chart.js settled; its bounded settled-layout rerun passes.
- Desktop and compact index screenshots were captured and inspected in screenshots/. Current CDN resources were reachable during this check; future CDN availability/bytes are not pinned by the template archive.

No native-device, installed Lyre binary, production service, backend authentication, email delivery, checkout, deployment, full accessibility audit or dependency security certification is claimed. This is an editable static website/UI template with sample content.
