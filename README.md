# Structural similarity and image upscaling (SSIM)

A historical set of experiments on how downscaling and upscaling affect image fidelity, using the structural similarity index (SSIM). The initial comparison of online image-upscaling services was developed with Lorenzo Caputi and Giorgio Micaletto as a student project at BAINSA.

## What is here

- `downscaling-percentages/` — repeated image rescaling at different ratios.
- `remini-test/` — an exploratory test involving the Remini API.
- `upscaling-software/` — image comparisons across upscaling tools.
- `requirements.txt` — dependencies for the original Python scripts.

The scripts are historical and may need updated file paths, image inputs, or API access. They are not intended as a maintained benchmarking package.

For the expanded, documented benchmark with reproducible results, see Lorenzo's [*Benchmarking image upscalers with the structural similarity index*](https://github.com/lorenzocaputi/upscaler-structural-similarity).

## Setup

```bash
pip install -r requirements.txt
```

This does not configure third-party API credentials or guarantee that historical endpoints still work.
