<div align="center">

# Hash Studio

**An approachable workbench for message digests.**

<sub>Security & developer tools &nbsp; · &nbsp; HTML · CSS · JavaScript &nbsp; · &nbsp; Open source code walkthrough</sub>

[Overview](#the-project) · [What to explore](#what-to-explore) · [Run locally](#run-locally) · [Source map](#source-map)

</div>

---

## The project

Compute SHA-256, SHA-384, and SHA-512 digests for text or local files using browser Web Crypto.

## What to explore

- SHA-256/384/512 via Web Crypto
- Hash local text or chosen files
- Keep file contents on the user device

## Run locally

```bash
python -m http.server 8000
```
Then visit **http://localhost:8000/**. For straightforward static demos, opening `index.html` directly may also work.

No online account is required unless the application explicitly requests one in its original documentation.

## Source map

| Path | Role |
| --- | --- |
| [`README.md`](./README.md) | Project documentation |
| [`app-base.js`](./app-base.js) | Shared browser utilities |
| [`app.js`](./app.js) | Interactive application logic |
| [`index.html`](./index.html) | Browser entry point and UI structure |
| [`style.css`](./style.css) | Visual design and responsive styling |

## Scope & responsible use

This is a portfolio-scale learning application. Keep experiments local and use synthetic or non-sensitive inputs; it is not a production security control.

<details>
<summary><strong>Original project documentation and further notes</strong></summary>

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

</details>

---

<sub>Maintained in the [Sharanya Pal GitHub portfolio](https://github.com/sharanyapal). Documentation describes the checked-in code rather than unverified production performance.</sub>
