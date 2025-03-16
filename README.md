# edge-debloat-macos
Debloat script for Microsoft Edge on macOS

Based on [the same thing but for Windows by marlock9](https://github.com/marlock9/edge-debloat).

Uses the Edge policies feature.

## Usage
Download and run the script:
```sh
curl -fsSL https://github.com/rev4324/edge-debloat-macos/blob/main/edge_debloat.sh | bash
```

## Back to defaults
```sh
rm /Library/Managed\ Preferences/com.microsoft.edge.plist
```