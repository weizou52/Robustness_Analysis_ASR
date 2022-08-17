This is the repository containing the code for the preprint "Analyzing robustness of end-to-end neural models for automatic speech recognition".

Slides for our work is available at presentation/presentation.pptx

# Notebooks/files to reproduce to experiments:

## Experiment E1 - Noisy waveform input

- wav2vec2 vs HuBERT on LibriSpeech - ```noise1_wv2_vs_hubert_revised.ipynb```
- wav2vec2 vs DistilHuBERT on TIMIT - ```final_timit_expt.ipynb```

## Experiment E2A - Layer noise injection
- Additive noise - ```final_white_noise_layers.ipynb```, needs dependency ```custom_wav2vec2.py```
- Multiplicative noise - ```final_multiplicative_noise_layers.ipynb```, needs dependency ```custom_mult_wav2vec2.py```

## Experiment E2B - Layer activation visualization
- ```visualization_expts.ipynb```