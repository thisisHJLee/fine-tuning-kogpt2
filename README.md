# fine-tuning-kogpt2

## Introduction
SKT가 공개한 KoGPT2 모델을 한국어 노래가사 20곡을 이용해 파인튜닝하였습니다. 적은 데이터로도 가사를 꽤 잘 생성합니다. 더 큰 데이터를 사용하면 성능도 더 좋아질 것으로 보입니다.

## About KoGPT2
KoGPT-2는 한국어로 학습된 오픈소스 기반 GPT-2 모델로, 질문에 대한 응답 생성, 문장 완성, 챗봇 등 한국어 해석이 필요한 여러 애플리케이션의 머신러닝 성능을 향상할 수 있습니다. GPT-2는 머신러닝 알고리즘을 활용해 입력된 샘플 텍스트를 구문론적, 문법적, 정보 등의 일관성을 갖춘 텍스트로 생성하는 자연어 처리 모델입니다. KoGPT-2는 챗봇 구축, 텍스트 감성 예측, 텍스트 분석 기반 응답 생성에 사용될 수 있습니다.

## Requirements
```
Windows 10 Pro
Python 3.8.16
Torch 1.8.0
CUDA 11.1
cuDnn 8.5.0
```

## References
- https://github.com/meanseo/readvice-KoGPT2-bookReport
- https://github.com/SKT-AI/KoGPT2
