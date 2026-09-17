# cctvtrack

Experimental browser-based truck-roof tracking and perspective projection of paludarium video onto moving vehicles.

## Build 002

Build 002 adds a manual-assisted perspective projection workflow:

1. Open the page.
2. Click four visible corners of a truck roof in clockwise order.
3. Once the roof plane is locked, drag any corner to calibrate it.
4. Adjust opacity, brightness, scanlines, and blend mode.
5. Optionally load another browser-readable video URL.
6. Clear or reset the target as needed.

The projection is rendered with a four-corner homography approximation directly in the browser canvas. The prototype is intentionally manual-assisted; automatic truck detection and motion tracking are future stages.

## Roadmap

- Improve WebGL performance for high-resolution sources.
- Add manual-assisted feature tracking.
- Add truck detection and target IDs.
- Add live CCTV source configuration.
- Deploy under a separate `cctvtrack.tallkidd.com` address.

This project is separate from `cctv.tallkidd.com`.
