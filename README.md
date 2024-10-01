# MovieSeq (ECCV'24)

![overview](./assets/teaser.png)

MovieSeq is a method designed to enhance Large Multimodal Models for improved video in-context learning using interleaved multimodal sequences (e.g., character photo, human dialogues, etc). 

We have developed a lightweight practical code that can be easily integrated into existing LMMs (e.g., GPT-4o) for easy usage.

## Environments
```
conda create --name movieseq python=3.10
conda activate movieseq
conda install pytorch==2.0.0 torchaudio==2.0.0 pytorch-cuda=11.8 -c pytorch -c nvidia

pip install git+https://github.com/m-bain/whisperx.git
pip install tqdm moviepy openai opencv-python
```

## Guideline
Please refer to `example.ipynb` to learn how MovieSeq works.
Have fun!
