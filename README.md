# TRS Pile Map

Interactive pile classification tool. Single static HTML page served via GitHub Pages.

## Updating

From the parent working folder:

```bash
python3 build_interactive_map.py
cp pile_heat_map_interactive.html trs-pile-map-site/index.html
cd trs-pile-map-site
git add index.html
git commit -m "Update pile data $(date +%Y-%m-%d)"
git push
```

GitHub Pages rebuilds automatically on push (usually within a minute).
