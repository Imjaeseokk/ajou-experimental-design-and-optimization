# Experimental Design and Optimization
### week1

## Orientation

- Regression Analytics
    - Linear / Non-linear
    - 단일변수 / 다변수
- Minitab
- 분산 분석, 완전 및 부분 요인 실험, 반응표면 실험, 혼합물 실험, EVOP 방법 등
- week3에 동영상 수업
- 동영상과 Zoom 병행 예정
- 09:20에 시작
- 출석: 2번 결석까지는 10점(만점)

## Lecture 1

- 예시 문제 풀이

### OFAT(One Factor At a Time)

- 한 번에 한 개의 변수 값 변경
- 하나의 변수만 변경하고 나머지 변수는 그대로 두면서 각 시행 결과를 표준과 비교
- 최적 공정 조건 도출은 어려움
- 여러 변수의 최적 조합을 탐색하기 어려움

### Keep The Winner

- 핵심요인 유지하기
- 좋은 결과를 보인 인자는 그대로 두고, 나쁜 결과를 보인 인자는 변경하는 전략

### 실험의 구성 요소

1. Factor(인자): 독립 변수 x
2. Response(반응): 독립 변수들에 의해 결과적으로 나타나는 종속 변수 Y
3. Error(오차): 반응에서 계측되지 않는 산포 잡음 e
- Deteministic Model과 Probabilistic Model

### 순차적인 실험

- 실험 설계 시, 몇 개의 작은 실험으로 나누어 설계하는 것이 효과적
- 순차 실험은 각각의 실험을 보다 용이하게 관리 가능
- 순차 실험은 목적하는 바에 좀 더 초점을 맞출 수 있음
- 순차 실험은 이전의 실험에서 습득한 바에 근거하여 행하여 질 수 있음
- 각 실험에서 얻은 경험을 좀 더 나은 실험을 설계하는데 사용함
- 실험이 진행되면서 정밀도 상승

Process

1. Screening(선별): 다수의 입력 변수들 중 **소수의 중요** 입력 변수 선별
2. Refining(특성화): 중요 입력 변수들이 출력변수에 **미치는 영향** 파악
3. Optimizing(최적화): 중요 입력 변수들의 **최적조건** 설정
- 완전 요인배치 실험: 변수의 두 조건 사이의 값들이 선형적
- 반응 표면 실험: 비선형적