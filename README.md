# Hash Studio

Compute SHA-256, SHA-384, and SHA-512 digests for text or local files using browser Web Crypto.

**Live application:** https://sp-hash-studio.vercel.app  
**Technology:** HTML, CSS, JavaScript  
**Visual direction:** Cryptographic vault  
**Source:** https://github.com/sharanyapal/sp-hash-studio

## Implemented functionality

- SHA-256/384/512 via Web Crypto
- Hash local text or chosen files
- Keep file contents on the user device

## Run locally

```bash
python -m http.server 8000
# Open http://localhost:8000
```

No build step or account required.

## Project structure

- `index.html` — semantic interactive application page
- `style.css` — independent responsive art direction and components
- `app.js` — application logic and input handling
- `app-base.js` — local browser utilities

## Safety and scope

A working portfolio-scale app, not a production security service. Local-only browser computation unless otherwise explained. No credentials are included.
