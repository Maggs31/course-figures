# course1/r7

Block diagrams for Recitation 7, referenced by this commit's raw URL. Redrawn after the papers named
below, sized to read on a projector without zooming. Architecture numbers are checked against the loaded models
in the notebook.

- `r7_chain.png`, The forward chain q and the reverse chain p_theta on a real image. After Ho et al. 2020, Fig 2.
- `r7_jump.png`, x_t in one jump from x_0 and eps. After Ho et al. 2020, eq 4.
- `r7_unet.png`, The DDPM CIFAR-10 U-Net with the label added. After Ho et al. 2020, App B, and the official code.
- `r7_resblock.png`, One residual block with the time vector added. After the official DDPM code (ResnetBlock).
- `r7_train.png`, One training step. After Ho et al. 2020, Algorithm 1.
- `r7_steps.png`, One ancestral step and one DDIM step from the same prediction. After Ho et al. 2020, Algorithm 2, and Song et al. 2021, eq 12.
- `r7_cfg.png`, Classifier-free guidance. After Ho and Salimans 2021, Algorithms 1 and 2.
- `r7_fid.png`, FID. After Heusel et al. 2017.
- `r7_pr.png`, Precision and recall for generators. After Kynkaenniemi et al. 2019, Fig 1.
- `r7_samples.png`, Samples of the two-hour class-conditional model at guidance 2, eight per class, drawn small as 32-pixel images should be.

The photo is scikit-image's chelsea (no copyright restrictions), cropped and resized to 256 by 256, noised here.
