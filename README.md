# FreePDFeditor

Static browser-based PDF tool. No API key, Node installation, backend or AI service is required.

## Run locally

From this folder run `python3 -m http.server 8000` and open http://localhost:8000. Use a web server rather than double-clicking index.html.

## GitHub Pages

Upload this folder’s contents to a repository root. In repository Settings → Pages, select Deploy from a branch, main, and / (root). Save and wait for GitHub to provide the site URL. A public repository and Pages deployment make the source and website publicly accessible.

## Limitations

Compression requires a maximum-size target; blank preserves quality and may leave the file unchanged. A target is not guaranteed. Strong compression can flatten searchable text and forms. Editing adds annotations rather than rewriting existing text. Typed signatures are visual marks, not certificate signatures. Review downloaded files and retain originals.

Input limit: 100 MiB/file; queue cap: 2,000 files; output budget: 256 MiB. These are implementation caps, not verified performance guarantees. Processing relies on available browser memory. No server upload is used for document processing. Google Fonts requests may occur.

## Dependencies

Third-party libraries and their licence notices are included in vendor/. This export excludes hosting credentials, test fixtures, and the private Sites project configuration. No licence for the original application code is granted by this README.

This export contains the deployed editor interface before the proposed two-option UI simplification.
