# CIFAR-10 CNN

A TensorFlow CNN for ten-class image classification with convolution, pooling, and batch normalization.

## Project status

Historical notebooks from Daniel Goldberg’s Kaggle account, organized for a maker portfolio. The model code is preserved, not rewritten during packaging. See [PROVENANCE.json](PROVENANCE.json) for original notebook URLs, timestamps, and SHA-256 hashes.

## Notebooks

- [notebooke3a86b3c6c.ipynb](notebooks/notebooke3a86b3c6c.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/notebooke3a86b3c6c)

## Running

Use the original Kaggle environment where possible: open the source notebook, attach its declared datasets/models, select the hardware expected by its setup cells, and run cells in order. Inspect any install, account-login, upload, or filesystem-changing cells before executing them.

For a local adaptation, install the packages listed in `requirements.txt` in an isolated environment and adjust `/kaggle/input` paths. Those packages are inferred from imports, **not** a tested lockfile. Historical APIs and accelerator assumptions can require changes. Do not run all training notebooks at once.

### Referenced Kaggle datasets

- [ayush1220/cifar10](https://www.kaggle.com/datasets/ayush1220/cifar10)

## Results and limitations

The original Kaggle directory layout must be attached or adapted. This is an early classification experiment, not a new benchmark claim.

The recovered Kaggle source exports contain no retained executed outputs; this repository therefore does not advertise a numeric result based on notebook titles or training settings. Training was not rerun as part of organization. Structural validation is not a runtime or scientific validation.

## Attribution and rights

Original notebook attribution, comments, and tutorial links are preserved. Standard TensorFlow/Keras examples and tutorial-style code should not be represented as newly invented algorithms. The precise human/AI/tool contribution history is not reconstructed by this archive. No blanket new license is assigned to third-party material. Datasets, pretrained models, and tutorial-derived content retain their own licenses and access requirements; their bytes are not bundled here.
