# cctvtrack

Experimental browser-based truck-roof tracking and perspective projection of paludarium video onto moving vehicles.

## Build 003

Build 003 adds a CCTV source layer with a Peace Bridge preset:

- `PEACE BRIDGE // CANADA-BOUND TRUCK INSPECTION`
- `LOCAL TEST VIDEO / NO CCTV`
- `CUSTOM EMBED URL`

The Peace Bridge preset opens the Buffalo and Fort Erie Bridge Authority traffic-camera page as a visual iframe source. The projection canvas remains above it, so the user can manually select four visible truck-roof corners and project the paludarium signal.

Because a cross-origin iframe cannot be read directly by the canvas, this build does not claim automatic pixel tracking from the Peace Bridge webpage. Direct tracking will require an authorized HLS, WebRTC, or same-origin video source.

## Roadmap

- Use a directly accessible authorized CCTV video source.
- Improve high-resolution rendering with WebGL.
- Add manual-assisted feature tracking.
- Add truck detection and target IDs.
- Deploy under `cctvtrack.tallkidd.com`.

This project is separate from `cctv.tallkidd.com`.
