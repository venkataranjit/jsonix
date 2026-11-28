# Jsonix

Jsonix is a browser-based collection of tools for working with JSON payloads, API logs, and encoded metadata.

## Tools

- **[API & JSON Studio](api-json-studio.html)** - Format API logs and JSON payloads, detect API structures, sort keys, and copy or export formatted results.
- **[JSON Formatter & Tree Inspector](json-formatter-tree-inspector.html)** - Validate JSON, choose indentation, inspect nested values in a collapsible tree, and copy paths or values.
- **[Base64 JSON Metadata Decoder](base64-json-metadata-decoder.html)** - Parse JSON metadata, find nested Base64 values, decode them, and inspect pipe-delimited fields.

## Getting Started

Jsonix has no build step or package dependencies.

1. Clone the repository:

   ```bash
   git clone https://github.com/venkataranjit/jsonix.git
   cd jsonix
   ```

2. Open `index.html` in a modern browser.

You can also serve the directory with any static file server:

```bash
# Python
python -m http.server 8000

# Open http://localhost:8000
```

## Features

- Runs entirely in the browser
- API log and general JSON auto-detection
- Configurable 2-space, 4-space, or tab indentation
- Optional alphabetical key sorting
- Syntax-highlighted JSON output
- Collapsible tree views with copyable JSON paths and values
- Recursive Base64 decoding
- Pipe-delimited field extraction
- JSON export and clipboard copy support
- Responsive dark developer interface

## Project Structure

```text
.
├── index.html                              # Landing page
├── api-json-studio.html                    # API log and JSON studio
├── json-formatter-tree-inspector.html      # JSON formatter and tree inspector
└── base64-json-metadata-decoder.html       # Base64 metadata decoder
```

## Privacy

Jsonix processes pasted input locally in the browser; JSON and API contents are not sent to analytics. Google Analytics 4 records page views, tool input activity, and identified button actions. The site does not require an account or application server. External CDN resources are used for Google Analytics, Tailwind CSS, fonts, and Lucide icons shown in the interface.
