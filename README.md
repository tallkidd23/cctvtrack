# cctvtrack

Experimental browser-based truck-roof tracking and perspective projection of paludarium video onto moving vehicles.

## Build 001

The first prototype is intentionally manual-assisted:

1. Open the page.
2. Click four visible corners of a truck roof in clockwise order.
3. Adjust opacity, brightness, and scanlines.
4. Clear or reset the target as needed.

The current projection preview uses a rectangular approximation inside the selected quadrilateral. Future builds can add true projective warping, feature tracking, automatic truck detection, and live CCTV input.

## Planned roadmap

- True four-corner homography warp using canvas/WebGL.
- Manual-assisted motion tracking.
- Truck detection and target IDs.
- Live CCTV source configuration.
- Cloudflare or GitHub Pages deployment under a separate cctvtrack subdomain.

This project is separate from `cctv.tallkidd.com`.
