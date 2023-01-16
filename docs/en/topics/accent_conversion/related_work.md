# Related Works

Accent coversion methods can be divided into two categories, reference-based and reference-free.

## Reference-based method

For the reference-based category [1][2][3], reference(target speaker's speech) should be provided in the inference process. The requirement of reference utterances during inference limits the practical use, so there are some methods trying to convert the accent without reference speech. 

## Reference-free method

There are also two categories of reference-free methods, parallel-data-based and non-parallel-data-based. 

### Parallel-data-based methods

Parallel-data-based approaches[4][5] essentially apply voice conversion or text-to-speech to generate parallel data(speech with source speaker timbre, source accent, source content and source speaker timbre, target accent, source content), firstly. Then the paired parallel data can be used as the input and output of the accent conversion module. 

### Non-parallel-data-based methods
Non-parallel-data-based approaches[6][7] try to decouple the content, speaker timbre and accent, and use the decoupled features reconstruct speech. In the inference stage, by controlling the accent, the conversion of the accent is realized

| ID | Paper                                                                                                                                                                         | Link |
|----|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| 1  | Guanlong Zhao et al. “Foreign Accent Conversion by Synthesizing Speech from Phonetic Posteriorgrams..” Conference of the International Speech Communication Association(2019) |   [paper](https://psi.engr.tamu.edu/wp-content/uploads/2019/07/zhao2019interspeech.pdf)   |
| 2  | Shaojin Ding et al. “Accentron: Foreign accent conversion to arbitrary non-native speakers using zero-shot learning” Computer Speech & Language(2021)                         |   [paper](https://www.sciencedirect.com/science/article/pii/S0885230821001029)   |
| 3  | Wenjie Li et al. “Improving Accent Conversion with Reference Encoder and End-To-End Text-To-Speech..” arXiv: Computation and Language(2020)                                   |   [paper](https://arxiv.org/abs/2005.09271)   |
| 4  | Guanlong Zhao et al. “Converting Foreign Accent Speech Without a Reference” IEEE/ACM transactions on audio, speech, and language processing(2021)                             |   [paper](https://psi.engr.tamu.edu/wp-content/uploads/2021/08/zhao2021reference.pdf)   |
| 5  | Tuan Nam Nguyen et al. “Accent Conversion using Pre-trained Model and Synthesized Data from Voice Conversion” (2023).                                                         |   [paper](https://www.isca-speech.org/archive/pdfs/interspeech_2022/nguyen22d_interspeech.pdf)   |
| 6  | Mumin Jin et al. “Voice-preserving Zero-shot Multiple Accent Conversion” (2022)                                                                                               | [paper](https://arxiv.org/abs/2211.13282)     |
| 7  | Dongya Jia et al. “Non-parallel Accent Conversion using Pseudo Siamese Disentanglement Network” (2022)                                                                        |   [paper](https://arxiv.org/abs/2212.05751)   |