# Source audit — 2026-11-09

## Reviewed sources

- Official source: https://worksinallthings.com/
- Official stylesheet: https://worksinallthings.com/assets/css/site.css
- Reference structure: https://branding.triumph.tech/ (navigation, a source-of-truth asset section, machine-readable `brand-kit.json`, repo/ZIP links)
- Reference requested but not retrievable in this environment: https://branding.hf.church/

## Extracted facts

| Area | Evidence | Guide decision |
| --- | --- | --- |
| Brand purpose | Homepage describes Rock RMS plugins for church staff and volunteers. | Lead with practical ministry support. |
| Logo | Homepage serves `logo.png` (1200×447) and WebP variants; the header uses an orange framed, uppercase text treatment. | Package the published raster logos unchanged; preserve the framed wordmark construction. |
| Mark | `/favicon.svg` contains an orange geometric W within a square frame. | Package as the only available scalable symbol, labeled as favicon/mark—not a substitute for an approved full logo vector. |
| Color | Site CSS explicitly names orange `#E87121`, grey `#E5E5E5`, dark base `#0C0D10`, and light accent `#F39552`. | Use these as the extracted core palette. |
| Type | Site CSS self-hosts Lato at weights 400 and 700. | Specify Lato for all guide UI and recommended brand work. |
| Voice | Copy includes “Thoughtful tools,” “Built the Rock way,” “Clean install and uninstall,” and “Real support.” | Write with clarity, usefulness, humility and specific operational detail. |
| Imagery | The reviewed home page is type-, logo-, and line-icon-led; no photography or illustration system was present. | Do not invent an imagery direction. Use product/UI or operational imagery only after approval. |

## Gaps / approval needed

1. An official vector full wordmark has not been located. Do not redraw or trace the raster logo.
2. Clear space, minimum size, incorrect-use examples, print colors, and co-branding rules are not published. The guide offers conservative working rules that need owner approval.
3. Publishing destination: this package was pushed to `Works-In-All-Things/branding` (WOR-12).
