# Transformer Model

## Transformer 모델 기반
- **LLM(Large Language Model)** 은 대부분 Transformer 모델을 기반으로 
설계되어 있다
- Transformer는 LLM의 핵심 아키텍처로, 대규모 언어 데이터를 학습하고 텍스트    생성, 이해, 변환 등의 작업을 수행하는 데 최적화된 구조이다
- LLM은 Transformer의 구조를 기반으로 하지만, 수십억에서 수조 개의 파라미터를 포함하며, 대규모 데이터를 학습할 수 있는 최적화된 버전이다

## Self-Attention 메커니즘
- LLM은 Transformer의 Self-Attention 메커니즘을 사용하여 입력된 텍스트 내 단어 간의 관계를 학습
- 예를 들어, "The cat sat on the mat"에서 "cat"과 "sat" 간의 관계를 학습하는 방식

## 대규모 병렬 처리
- LLM은 Transformer의 병렬 처리 능력을 활용해 대규모 데이터를 학습할 수 있다
- GPU, TPU 같은 하드웨어 가속기의 성능을 극대화 한다

## GPT 시리즈 에서 Transformer 사용 예시
- OpenAI의 GPT-3, GPT-4는 Transformer의 디코더(decoder) 구조를 사용
    - 디코더(decoder) 구조:
        - 디코더는 **입력(인코더 출력)** 과 이전 디코더의 출력을 결합하여 최종 출력값을 생성하는 방식으로 작동
    
## LLM에서 Transformer의 이점
1. 확장성
- Transformer는 대규모 병렬 처리가 가능해, 수십억 개의 파라미터를 처리하는 LLM에 적합
2. 장기 의존성 학습
- Self-Attention 메커니즘을 통해 텍스트 내 멀리 떨어진 단어 간의 관계도 잘 학습
3. 범용성
- 번역, 텍스트 생성, 요약, 코드 생성 등 다양한 작업에 적응 가능
4. 효율성
- RNN이나 LSTM보다 학습 속도가 빠르고, GPU 및 TPU를 효율적으로 활용

