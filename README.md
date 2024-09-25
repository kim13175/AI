# capstone
---
1. Feature Selection
2. Text data preprocessing
---

- 보고서 결과 - 입력값 / 특이점 발견 유무 - 라벨

- 텍스트 전처리 사용 기술 : 특수문자, 불용어 제거 / dmis-lab biobert를 이용한 토큰화 / 시퀀스 prepadding

원문 링크 : https://www.notion.so/1-LSTM-text-preprocessing-10c47c6c0642807b8f89f17e898499fe?pvs=4

---

3. model analytics
---

- lstm 기본 모델을 이용한 이진 분류 성능 평가

  - 결과 : 단방향 lstm layer를 2개 사용하고 이전 lstm 층에서 출력뿐 아니라 내부 시퀀스들도 두 번째 lstm층에서 입력받아 출력층을 거쳐 출력값을 내는 것이 제일 성능이 좋았음

  - 추가 진행 예정 사항 : 오버피팅이 일어난 것을 확인 -> 드롭아웃을 적용시키려고 함 / 긴 시퀀스 길이에 의한 장기기억력이 필요하기에 lstm 내부 파라미터의 dropout을 이용하는 것이 좋다고 생각하고 진행 예정

원문 링크 : https://www.notion.so/2-LSTM-Model-10c47c6c064280a69631e248e7abe3d0?pvs=4
