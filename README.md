# Speech
First speech research, have fun~

本项目为语音模型的学习项目，目前总共有三个部分：

1. 语音SSL模型的复现
2. Benchmarks的使用
3. 语音技术基础

## 1. 语音SSL模型的复现
1. 理解各个模型的原理和代码：[Speech_SSL.ipynb](Speech_SSL.ipynb)
2. 学习使用[Transformer](https://github.com/huggingface/transformers)库：[Speech_Processing.ipynb](Speech_Processing.ipynb)
3. 梳理和比较不同的模型之间的共性和差异：[Speech_Probe.ipynb](Speech_SSL.ipynb)

### 1.1 语音SSL模型包括
1. [Wav2vec 2.0](https://arxiv.org/abs/2006.11477) 
2. [HuBERT](https://arxiv.org/abs/2106.07447)
3. [WavLM](https://arxiv.org/abs/2110.13900)
4. SpeechLM
5. Whisper（并不是SSL，但是也研究一下）

除了以上模型，还有一些其他感兴趣的模型：

1. SpeechToTextTransformer(2)
2. Unispeech
3. Wav2Vec2-Conformer
4. Wav2VecPhoneme
5. XLSR-Wav2Vec

### 1.2 Transformer库

### 1.3 模型比较和可解释性工作

## 2. Benchmarks的使用
1. 对语音的数据和数据库进行调研
2. 学会使用[SUPERB Benchmark](https://github.com/s3prl/s3prl)
3. 其他库：SUPERB-SG 和 **SUPERB-prosody**
4. 跑一下模型的结果

### 2.1 语音数据库
### 2.2 SUPERB Benchmark
代码：[SUPERB.ipynb](SUPERB.ipynb)
### 2.3 SUPERB SG
## 3. 语音技术基础