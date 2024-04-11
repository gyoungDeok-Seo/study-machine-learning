### AI (Artificial Intelligence)  
<img src="./a_intro/images/intro.png" width="800px">  

#### Rule-base AI
- 특정 상황을 이해하는 전문가가 직접 입력값(문제)과 특징을 전달(규칙)하여 출력값(정답)을 내보내는 알고리즘이다.
- 광범위한 데이터 수집, 정리 또는 교육이 필요하지 않으므로 전문가의 기존 지식을 기반으로 비지니스 규칙을 정의하여 구현 복잡성을 줄일 수 있다.
- 의사 결정 프로세스가 명시적인 "if-then" 사전 정의 규칙에 의존하므로 높은 투명성을 제공한다.
- 본질적으로 정적이며 유연성이 없기 때문에, 사전 정의된 규칙을 수동으로 조정하여 변화나 진화하는 조건에만 적응할 수 있다.
- 사전 정의된 규칙이 명확한 지침을 제공하지 않는 모호하거나 불확실한 상황에 직면할 때 어려움을 겪을 수 있다.
- 미리 정의된 기준에 의존하면, 전문가 개인의 편견이 들어갈 수 밖에 없고, 이로 인해 미묘한 행동을 설명하지 못할 수 있으며 잠재적으로 불공평하거나 부정확한 평가로 이어질 수 있다.

#### Machine Learning AI
- 데이터를 기반으로 규칙성(패턴)을 학습하여 결과를 추론하는 알고리즘이다.
- 현실 세계의 패턴을 분석하여 개발자가 직접 코드를 작성하는 것이 어려웠으나 머신러닝을 이용해서 해결할 수 있다.
- <sub>※</sub> 데이터 마이닝, 음성 인식(언어 구분), 영상 인식(이미지 판별), 자연어 처리(번역, 문맥 찾기)에서 머신러닝이 적용된다.  
<sub>※ 데이터 마이닝이란, 대규모 데이터 안에서 체계적이고 자동적으로 통계적 규칙이나 짜임을 분석하여 가치있는 정보를 빼내는 과정이다.</sub>
- 데이터의 패턴을 학습하여 이를 통해 예측 등을 수행할 수 있다.  

1. 지도 학습 (Supervised Learning)  
   
   > 입력값(문제)과 출력값(정답)을 전달하면, 알아서 특징을 직접 추출하는 방식이다.
   > 다른 입력값(문제)과 동일한 출력값(정답)을 전달하면 새로운 특징을 알아서 추출한다.

   > 문제(Feature)와 답(Target, Label)을 주는 것이다.
   > - 분류 (코로나 양성/음성, 사기 번호/일반 번호 등 단일 값 예측)
   > - 회귀 (1년 뒤의 매출액, 내일 주식 가격 등 연속 값 예측)
  
2. 비지도 학습 (Unsupervised Learning)
   
   > 입력값(문제)만 전달하고 정답 없이 특징만 추출하는 학습이다.
   > 추출한 특징에 대해 AI가 출력값(정답)을 부여하여 입력값(문제)은 출력값(정답)이라는 것을 알아낸다.

   > 문제(Feature)를 주고 답은 주지 않는 것이다.
   > - 군집화 (클러스터링, 비슷한 문제를 분석하여 편을 나누어 각 편으로 모으는 것)
   > - 차원 축소 (문제의 개수를 압축(축소)하여 함축된 의미를 찾아내는 것)

3. 강화 학습 (Reinforcement Learning)  

> https://kr.mathworks.com/discovery/reinforcement-learning.html

#### Machine Learning의 단점
- 데이터에 의존적이다 (Garbage In, Garbage Out), 데이터가 안좋으면 결과도 안좋을 수 밖에 없다.
- 학습 데이터로 잘 만들어진 로직을 가진 모델일지라도 실제 데이터 적용 시 정확한 결과가 나오지 않을 수 있다.
- 머신러닝 학습을 통해 로직이 생기면, 나온 결과가 어떻게 이렇게 나왔는 지에 대한 분석이 쉽지 않다(블랙박스).
- 데이터를 넣으면 원하는 것처럼 좋은 결과를 얻기란 쉽지 않다.

#### R vs Python

- R  
  
> 개발 언어에 익숙하지 않지만 통계 분석에 능한 현업 사용자일 경우
> 오랜 기간동안 쌓인 다양하고 많은 통계 패키지

- Python  

> 직관적인 문법, 객체지향 함수형 프로그래밍언어, 다양한 라이브러리
> 다양한 영역 (운영체제, 서버, 네트워크 등)으로 연계 및 상용화하기 좋음

### 머신러닝과 딥러닝은 R보다는 "파이썬"을 사용하자!
