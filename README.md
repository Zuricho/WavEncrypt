# WavEncrypt
Integrate encrypted messages into audio file 


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
conda install huggingface_hub -c conda-forge
```

For wavmark, the paramaters are directly downloaded from HuggingFace: https://huggingface.co/M4869/WavMark



