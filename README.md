# Transformer 학습 자료

> 졸업연구 [「Transformer 인코더 기반 탠덤 질량 스펙트럼 노이즈 피크 판별」](https://github.com/hwhw98/gradProj)을 준비하며
> 연구실에서 매주 발표한 자료입니다. (2022)

딥러닝 기초부터 Attention, Transformer 인코더, TensorFlow 구현 코드까지 단계적으로 정리했고,
이 내용을 바탕으로 졸업연구에서 Transformer 인코더를 직접 구현했습니다.

## 발표 자료 (`peptide_sequence_transformer.zip`)

| 순서 | 파일 | 내용 |
|---|---|---|
| 1 | `neural_network.pptx` | 인공신경망 기초: 활성함수, 손실함수, 역전파, 경사하강법, 기울기 소실, CNN |
| 2 | `gene_sequence_learning.pptx` | 연구 배경: 드노보 펩타이드 시퀀싱, 질량 스펙트럼과 m/z·상대 세기의 의미 |
| 3 | `tensorflowTransformer.pptx` | TensorFlow 공식 Transformer 튜토리얼 코드 분석: 토큰화, 패딩, 포지셔널 인코딩, 마스킹 |
| 4 | `atttention.pptx` | Scaled Dot-Product Attention과 Multi-Head Attention 구현 |
| 5 | `transformer_encoder.pptx` | Encoder Layer와 Encoder 구현: 임베딩, 포지셔널 인코딩, N개 레이어 쌓기 |

## 참고

- Vaswani et al., *Attention Is All You Need*, 2017
- [TensorFlow Transformer tutorial](https://www.tensorflow.org/text/tutorials/transformer)
