# EnvSDD project page

Source of <https://envsdd.github.io/>, the project page for
**EnvSDD: Benchmarking Environmental Sound Deepfake Detection** (Interspeech 2025).

- Paper: <https://arxiv.org/abs/2505.19203>
- Code & dataset: <https://github.com/apple-yinhan/EnvSDD>
- ESDD 1 challenge overview (ICASSP 2026): <https://arxiv.org/abs/2603.04865>
- ESDD 2 challenge overview (ICME 2026): <https://arxiv.org/abs/2606.10791>

## Layout

- `index.html` — the whole page; CSS and JS are inline, no build step.
- `static/audios/<dataset>/<key>.mp3` — demo clips (`real`, `tta-*`, `ata-*`).
- `static/images/` — favicon, method figure, social preview card (`social.png`, 1200×630).

## Updating

Edit `index.html`, preview locally with `python3 -m http.server`, then push to `main`.
GitHub Pages serves the `main` branch root directly, so every push to `main` goes live.
