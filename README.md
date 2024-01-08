# Memory-Efficient-Audio-Spectrogram-Tranformer-Model

This repository contains the implementation for Memory Efficient Audio Melspectrogram Tranformer Model (MEAMTM) which utilizes nnAudio and the Audio Spectrogram Transformer to offer a memory-efficient solution for audio classification. With this model, you can directly feed audio waveforms without the need to convert them into spectrograms separately, saving both storage and memory.

# Introduction
The model eliminates the need for intermediate spectrogram conversion, reducing memory and storage requirements and improving efficiency. This also increases ease of use, as audio processing is handled directly by the model. This model also leverages transformer introduced in [AST: Audio Spectrogram Transformer](https://arxiv.org/abs/2104.01778).

# TODO
* fix readme: add architecture, add results on ESC-50 dataset
* convert the notebook to python scripts

# References

@ARTICLE{9174990, author={K. W. {Cheuk} and H. {Anderson} and K. {Agres} and D. {Herremans}}, journal={IEEE Access}, title={nnAudio: An on-the-Fly GPU Audio to Spectrogram Conversion Toolbox Using 1D Convolutional Neural Networks}, year={2020}, volume={8}, number={}, pages={161981-162003}, doi={10.1109/ACCESS.2020.3019084}}

@article{dosovitskiy2020vit,
  title={An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale},
  author={Dosovitskiy, Alexey and Beyer, Lucas and Kolesnikov, Alexander and Weissenborn, Dirk and Zhai, Xiaohua and Unterthiner, Thomas and  Dehghani, Mostafa and Minderer, Matthias and Heigold, Georg and Gelly, Sylvain and Uszkoreit, Jakob and Houlsby, Neil},
  journal={ICLR},
  year={2021}
}

@ARTICLE{gong_psla, 
    author={Gong, Yuan and Chung, Yu-An and Glass, James},  
    journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing},   
    title={PSLA: Improving Audio Tagging with Pretraining, Sampling, Labeling, and Aggregation},   
    year={2021}, 
    doi={10.1109/TASLP.2021.3120633}
}
