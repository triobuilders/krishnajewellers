SHREE KRISHNA JEWELLERS — FIXED PWA PACKAGE

Files: index.html, manifest.webmanifest, sw.js, icons, and notes. This is the website/PWA source package, not a signed IPA or APK.

PWABuilder: Publish all files at the root of an HTTPS website. index.html now links manifest.webmanifest and the Apple touch icon. Enter the live HTTPS URL in PWABuilder rather than uploading this ZIP into a field that expects an app name or URL.

GitHub Pages: Upload the CONTENTS of this ZIP to the repository root, not the ZIP itself. Ensure index.html and manifest.webmanifest are at the same root level.

Data: Customer, stock, girvi, settings, and advance orders are stored in this browser/device. Advance orders are now persisted and included in encrypted backup. Browser storage can still be erased; make regular encrypted backups.

Backup: Use the app backup screen on HTTPS. The exported .skjbackup is encrypted with AES-256-GCM. Keep the backup password separately; it cannot be recovered.

Privacy: Do not put customer data or backups in GitHub. Live browser storage is not encrypted at rest. This package has passed archive and syntax checks, not a full security audit or device test.

Apple/iPhone: PWABuilder may generate an iOS project package; producing a signed installable IPA requires Apple signing and an iOS build workflow (usually Xcode on macOS or a compatible service).
