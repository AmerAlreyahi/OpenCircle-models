# OpenCircle models

Offline translation models that [OpenCircle](https://github.com/AmerAlreyahi/OpenCircle) downloads on demand.
OpenCircle checks every file against a SHA-256 fingerprint built into the app; a file that doesn't match is refused.

These files are ONNX conversions (int8-quantised, Xenova/transformers.js layout) of Helsinki-NLP's OPUS-MT models,
made by OpenCircle with `scripts/convert-mt-models.py` in the OpenCircle repository from the pinned source revisions
listed in each release's `manifest.json`.

## Credits and licence

OPUS-MT models by Helsinki-NLP (University of Helsinki), https://huggingface.co/Helsinki-NLP — licensed CC BY 4.0
(https://creativecommons.org/licenses/by/4.0/). Changes: converted to ONNX and quantised.

Tiedemann, J. and Thottingal, S. (2020). OPUS-MT — Building open translation services for the World.
Proceedings of EAMT 2020.

The model files are not covered by OpenCircle's MIT licence; they keep their own licence above.
