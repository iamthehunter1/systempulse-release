# SystemPulse Optimizer — Binaries Only

Prebuilt desktop binaries. Source is not published here.

## Downloads
Get the latest release from the Releases page:
- Linux: `systempulse-linux.tar.gz`
- Windows: `systempulse-windows.zip` (or `.tar.gz`)
- macOS: `systempulse-mac.tar.gz`

## Verify
- Linux/macOS: `sha256sum -c SHA256SUMS.txt`
- Windows (PowerShell): `Get-FileHash .\systempulse.exe -Algorithm SHA256`

## Run
- Linux: `tar -xzf systempulse-linux.tar.gz && chmod +x systempulse && ./systempulse` (or `./systempulse.sh`)
- Windows: extract, then run `systempulse.exe`
- macOS: `tar -xzf systempulse-mac.tar.gz && chmod +x systempulse-mac && ./systempulse-mac`  
  If blocked, right-click → Open once or allow in System Settings → Privacy & Security.

## Notes
- Session-only tweaks; changes auto-revert.
- No guaranteed FPS gains; results vary by hardware and game.
