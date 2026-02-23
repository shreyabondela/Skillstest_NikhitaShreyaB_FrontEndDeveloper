# Jessica Taylor Patient Dashboard

Single-page responsive dashboard built from the provided skills-test prompt.

## Run locally

```bash
python3 -m http.server 4173
```

Open `http://127.0.0.1:4173`.

## Files

- `index.html` - page structure
- `styles.css` - styling and responsive behavior
- `script.js` - API fetch + render logic (Jessica Taylor only)

## Notes

- If the API cannot be reached in a restricted environment, the page uses a local Jessica Taylor fallback dataset so the UI still renders correctly.
