<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## EDM-HSE Dataset

EDM-HSE is an open audio dataset containing a collection of code-generated drum recordings in the style of modern electronic house music. It includes 8,000 audio loops recorded in uncompressed stereo WAV format, created using custom audio samples and a MIDI drum dataset. The dataset also comes with paired JSON files containing MIDI note numbers (pitch) and tempo data, intended for supervised training of generative AI audio models.

## Overview

The EDM-HSE Dataset was developed using an algorithmic framework to generate probable drum notations commonly played by EDM music producers. For supervised training with labeled data, a variational mixing technique was applied to the rendered audio files. This method systematically includes or excludes drum notes, assisting the model in recognizing patterns and relationships between drum instruments, thereby enhancing its generalization capabilities.

The primary purpose of this dataset is to provide accessible content for machine learning applications in music and audio. Potential use cases include generative music, feature extraction, tempo detection, audio classification, rhythm analysis, drum synthesis, music information retrieval (MIR), sound design and signal processing.

**Specifications**

- 8,000 audio loops (approximately 17 hours)
- 24-bit WAV format
- Tempo range: 120–130 BPM
- Paired label data (WAV + JSON)
- Variational drum patterns
- Subgenre styles (Big room, electro, minimal, classic)

A JSON file is provided for referencing and converting MIDI note numbers to text labels. You can update the text labels to suit your preferences.

## Examples

See examples folder to preview mp3 demos.


## License

This dataset is developed by WaivOps, a crowdsourced music project managed by sound label company Patchbanks. All recordings have been compiled by verified sources for copyright clearance.

The EDM-TR9 dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
## Download

The audio files are provided in 24-bit WAV format and encoded at 44.1kHz.

Direct WAV Download (7.6GB) [edm_hse_id_001-004_wav.tar.gz](https://zenodo.org/records/10278066/files/edm_tr9_drm_id_001.tar.gz?download=1)

Direct JSON Download (245KB) [edm_hse_id_001-004_json.tar.gz](https://zenodo.org/records/10278066/files/edm_tr9_drm_id_001.tar.gz?download=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10278066.svg)](https://doi.org/10.5281/zenodo.10278066)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| edm | Main genre (edm)|
| drm | instrument (drums)|
| id | Identification number|
| _00 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@misc{EDM-TR9,
author = {WaivOps},
title = {WaivOps EDM-HSE: Open Audio Resources for Machine Learning in Music},
year = {2024},
doi = {10.5281/zenodo.13769544},
url = {https://doi.org/10.5281/zenodo.10278066},
}
```
## Additional Info

Please note that this dataset has not been fully reviewed and may contain minor notational errors or audio defects.

For any questions or feedback please email info@patchbanks.com.
