# WavEncrypt

Integrate encrypted messages into audio file.

This is the course project for CUHK EE ELEG 5421 Audio signal processing


# Installation

Install the environment using conda

- Installation test system: MacOS Sequoia 15.1.1 
  - (Since arcosx is highly restrictive, this installation should be working for most of Win & Linux systems)

```bash
conda create -n audio python=3.10
conda install matplotlib numpy pandas scikit-learn scipy
conda install -c conda-forge librosa 
conda install -c conda-forge pysoundfile     
conda install ipykernel

conda install pytorch torchaudio -c pytorch
conda install tqdm -c conda-forge
conda install resampy -c conda-forge
conda install huggingface_hub -c conda-forge  # this might not needed now
```

For wavmark, the paramaters are directly downloaded from HuggingFace: https://huggingface.co/M4869/WavMark. Parameters are stored in the folder `wavmark_params`.

# Usage

Follow the steps in `wavencrypt.ipynb`

