# DFA - Design for Assembly

Design for Assembly web app (static HTML/CSS/JS). Data is stored in the browser `localStorage`.

## Run locally

```bash
python -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765/

See `RUN-LOCALHOST.md` for details.

## Pages

- `index.html` — start / selection
- `revup.html` / `newdfa.html` — DFA intake
- `pfd.html` — process flow (image, **step name**, description)
- `amr-requirements.html` — AMR statuses
- `amr-facility-analysis.html` — facility impact by category
- `report.html` — report + A4 PDF export
- `all-dfas.html` — all DFAs table
