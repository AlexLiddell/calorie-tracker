# Local Calorie Tracker (Offline PWA) - v2 (with camera barcode scan)

## Camera barcode scan (best-effort)
- Uses the browser BarcodeDetector API when available.
- If unsupported on your iPhone/iOS version, you can still type the barcode manually.

## iPhone install (Safari)
1. Host these files somewhere reachable via URL (HTTPS recommended).
2. Open the URL in Safari.
3. Share → Add to Home Screen.

## Notes
- Data stays on-device (localStorage). Export JSON for backups.
