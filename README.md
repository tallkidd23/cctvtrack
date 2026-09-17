# cctvtrack

Experimental browser-based truck-roof tracking and perspective projection of paludarium video onto moving vehicles.

## Build 004

The default CCTV sources are now Laredo / Nuevo Laredo bridge-camera portals:

- Laredo // Puente 2 / Juárez-Lincoln
- Nuevo Laredo // Puente 3 / Colombia Solidarity
- Laredo // Puente 4 / World Trade
- Local test video
- Custom embed URL

The bridge presets use a visual portal iframe. Depending on the provider, the page may show refreshed camera images or an embedded view rather than a continuous browser-readable stream. Because a cross-origin iframe cannot be read directly by the canvas, this build does not claim automatic pixel tracking from the portal. Direct tracking will require an authorized HLS, WebRTC, or same-origin video source.

## Roadmap

- Use a directly accessible authorized CCTV video source.
- Improve high-resolution rendering with WebGL.
- Add manual-assisted feature tracking.
- Add truck detection and target IDs.
- Deploy under `cctvtrack.tallkidd.com`.

This project is separate from `cctv.tallkidd.com`.
