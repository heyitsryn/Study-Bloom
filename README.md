# Study Bloom

A local-first, installable student planner PWA. No account, server, analytics, framework, or internet connection is required after first load.

## Run locally
PWA installation and service workers require http/https, not a file:// URL.

1. Open a terminal in this folder.
2. Run `python3 -m http.server 8080`.
3. Visit `http://localhost:8080`.
4. Use the browser's Install or Add to Home Screen command.

## Deploy
Upload the folder as-is to any static HTTPS host. Data stays in the browser's local storage. Use Settings > Export backup regularly.
