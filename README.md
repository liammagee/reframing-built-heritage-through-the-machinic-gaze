# (Re)framing Built Heritage through the Machinic Gaze

This repository contains data used in:

    Arora, V., Magee, L., & Munn, L. (2023). (Re)framing Built Heritage through the Machinic Gaze. arXiv preprint arXiv:2310.04628.

The three main directories contain outputs from three generative image models:

1. Midjourney 5.2
2. Stable Diffusion XL (SDXL) 1.0
3. Realistic Vision 1.3 (an adaptation of SD 1.5)

Each of these directories contains in turn 5 folders, corresponding to 5 heritage sites discussed in the paper:

- DJENNE
- KASUBI
- KOSOVO
- SANAA
- SHAKHRISYABZ

Each of these, in turn, contains 'H-M' (human prompt - machine generated) and 'M-M' (machine prompt - machine generated), each with 4 respective images. The procedure for how these files are produced is outlined in the paper. In the case of Midjourney, files were produced via Discord, while in the cases of SDXL and RealisticVision, files were produced via a script calling the [Replicate service](https://replicate.com/).
