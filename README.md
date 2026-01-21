# Tools in HTML

A collection of single-file HTML tools. Each tool is an independent HTML file that runs entirely in the browser with no backend required.

Inspired by [Simon Willison's Tools](https://tools.simonwillison.net).

## Tools

| Tool | Description |
|------|-------------|
| [base64](base64.html) | Base64 encoding/decoding with Unicode support |
| [countdown](countdown.html) | Countdown timer with shareable links |
| [converter](converter.html) | JSON/YAML/TOML format converter |
| [diff](diff.html) | Side-by-side text comparison |
| [duration](duration.html) | Calculate duration between two timestamps |
| [json](json.html) | JSON formatter/minifier with folding |
| [password](password.html) | Configurable password generator |
| [rsa](rsa.html) | RSA private key parser |
| [certificates](certificates.html) | X.509 certificate parser |
| [brewfile](brewfile.html) | Homebrew Brewfile analyzer with dependency graph |
| [image](image.html) | Docker/OCI container image analyzer |

## Tech Stack

- **HTML5 + CSS3 + Vanilla JavaScript**
- **CodeMirror 5** - Code editor (converter, json, brewfile)
- **Flatpickr** - Date/time picker (countdown, duration)
- **Cytoscape.js** - Graph visualization (brewfile)

## Design

- Dark theme (deep blue/purple gradient background)
- Frosted glass effect cards
- Responsive layout
- All processing done client-side for privacy
