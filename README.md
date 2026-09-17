# cctvtrack

## Build 007 — live screen capture

Build 007 adds a browser-permission-based screen-capture input. It does not scrape or bypass a camera provider’s stream.

### Workflow

1. Open the Times Square North 4K camera in another browser tab.
2. Return to cctvtrack.
3. Tap **START SCREEN CAPTURE**.
4. Choose the Times Square tab in the browser picker.
5. Allow video sharing.
6. Place four corners over the desired projection surface.
7. Adjust opacity, brightness, scanlines, and blend mode.
8. Tap **STOP CAPTURE** when finished.

### Sources

- Times Square North 4K.
- EarthCam Times Square.
- Otay Mesa SR-905.
- Otay Mesa commercial gateway.
- Local test video.
- Custom camera page URL.

The screen-capture path requires browser support for `navigator.mediaDevices.getDisplayMedia()` and a user gesture. A third-party camera page may still block iframe embedding, so use **OPEN CAMERA** first, then capture that tab.
