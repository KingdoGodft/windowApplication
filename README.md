# fpsPrediction
FPS 예측 머신러닝 기능

## 요구사항 분석
1번 데이터 
-CPU : PassMark CPU Mark / Clockspeed / Cores / Threads
-GPU: PassMark GPU Mark / Max Memory Size / Core Clock
2번데이터
-게임별 저사양, 중사양, 고사양 PC의 최소 최대 FPS 데이터 (크롤링 혹은 API)

2번 데이터 PC의 정보들을 학습시켜 1번 데이터를 테스트 하여 FPS 예측 기능 개발한다

Pytorch을 활용한 예측 머신러닝 기법 사용
-Pytorch 선택 사유 : 파이썬과 유사함에 따라 진입 장벽이 낮다
