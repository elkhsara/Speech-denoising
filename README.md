This repository contains the tutorial for a speech denoising project.

The data is open-source and has been upoladed from the following link: https://www.openslr.org/12.

Speech enhancement aims to improve the quality and intelligibility of speech signals by reducing or eliminating unwanted noise and distortions.
The approach is supervised and involves improving the quality of a speech signal by leveraging the training dataset with paired examples of clean and noisy speech signals.
The data is going to be noised then spectrograms of both the noised and original audios will be fed to multiple architectures of deep learning to conduct a comparison on the performance.
First a simple Feed Forward Neural Net was trained as a baseline and then an LSTM was trained as they are more convienent to treat sequential data such as speech.

The evaluation is done by comparing the Signal to Noise Ratio SNR of both the audios.
