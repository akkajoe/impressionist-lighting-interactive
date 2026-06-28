# impressionist-lighting-interactive

Interactive 3D visualization of estimated light directions across 1,394 Impressionist paintings, as described in "Quantifying Lighting Consistency in Impressionist Painting" (CHR 2026).

## Live demo

Available at [URL removed for anonymous review].

## Structure

- `site_ev00/`: the interactive site (index.html and supporting files)
- `data/`: painting images
- `balls/`: synthesized chrome ball images
- `plots_embedded/`: per-painting light direction arrow plots
- `site_data/`: points.json containing the full corpus of directional estimates
- `website.py`: script used to generate the site from pipeline outputs

## Usage

To view locally:

```bash
cd site_ev00
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.
