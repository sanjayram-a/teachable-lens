# Teachable Lens — deck

**Live:** https://sanjayram-a.github.io/teachable-lens/

A 5-slide BlockFrame deck for the Teachable Lens demo (CLIP ViT-B/32 embeddings + a
logistic-regression head, CPU only). Single self-contained `index.html` — no build step,
no dependencies beyond Google Fonts.

## Navigate

| Action | Control |
| --- | --- |
| Next slide | `→` `Space` `PageDown` · swipe left |
| Previous slide | `←` `PageUp` · swipe right |
| Fullscreen | `F11` |
| Export to PDF | `Ctrl`+`P` → Save as PDF (one slide per page) |

## Update the deck

```bash
cp "Teachable Lens.html" index.html   # from the image-classification repo
git commit -am "update deck" && git push
```

Pages rebuilds automatically in ~30-60 s.
