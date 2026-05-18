# ai-image-prompt-breakdown-assets

Public asset repository for Hermes skill `ai-image-prompt-breakdown`.

## Purpose

This repository stores public image assets used by the workflow so downstream model requests can reference HTTPS URLs instead of embedding large local images as base64 data URLs.

## Layout

```text
runs/
  workflow-<run_id>/
    sample_images/
    stage_e/
    stage_g/
    stage_h/
```

## Notes

- This repo is intentionally public so jsDelivr CDN URLs can access assets.
- Assets should be treated as immutable once uploaded.
- Prefer unique `workflow-<run_id>` directories instead of overwriting old paths.
