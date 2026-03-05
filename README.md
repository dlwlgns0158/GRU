# GRU
RNN - GRU    Research Methodology Seminar


GRU (Gated Recurrent Unit)**는 시계열·문장처럼 순서가 있는 데이터를 다루는 RNN의 한 종류.

기존 RNN은
오래된 정보를 잘 기억하지 못하는 문제(기울기 소실)가 있음 → 이를 해결하기 위해 게이트(gate) 구조를 사용

GRU는 2개의 게이트로 정보 흐름을 조절
Update Gate (z) → 과거 정보를 얼마나 유지할지 결정
Reset Gate ® → 과거 정보를 얼마나 무시할지 결정

장점
LSTM보다 구조가 단순 (게이트 2개)
연산이 빠르고 성능도 준수
시계열 예측, 자연어 처리에 자주 사용

GRU는 “중요한 과거 정보는 남기고, 필요 없는 정보는 잊도록” 설계된 RNN








