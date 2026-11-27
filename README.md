# Text sample QA images

Side-by-side renderings of `scripts/text_samples.py` for the EMF PR: Windows
GDI (`PlayEnhMetaFile` on Windows Server 2025, the runner's installed fonts) on
the left, pillow-wmf (`SystemFontCollection` with the Microsoft core fonts) on
the right. `*-zoom.png` enlarge the top-left corner three times.

Regenerate with the `text-samples` probe, then
`python scripts/text-samples-side-by-side.py NATIVE_DIR OUTPUT_DIR`.
