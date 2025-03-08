# MovieSeq (ECCV'24)
[arXiv](https://arxiv.org/abs/2407.21757)

![overview](./assets/teaser.png)

MovieSeq is a method designed to enhance Large Multimodal Models for improved **video in-context learning using interleaved multimodal sequences** (e.g., character photo, human dialogues, etc). 

> Recognize the baseline used in the paper LLama2 is quite old, we have developed **MovieSeq-4o** -- lightweight practical code that can be easily integrated into existing LMMs (e.g., GPT-4o) for easy usage.

**MovieSeq-4o** connects Whisper, Character images, and Frames to build a good video context, it can easily integrate into other VLM or APIs (such as Gemini, Claude, etc) on your own videos!

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

## BibTeX
If you find our work helpful, please kindly consider citing our paper. Thank you!
```
@inproceedings{lin2024learning,
  title={Learning video context as interleaved multimodal sequences},
  author={Lin, Kevin Qinghong and Zhang, Pengchuan and Gao, Difei and Xia, Xide and Chen, Joya and Gao, Ziteng and Xie, Jinheng and Xiao, Xuhong and Shou, Mike Zheng},
  booktitle={European Conference on Computer Vision},
  pages={375--396},
  year={2024},
  organization={Springer}
}
```
