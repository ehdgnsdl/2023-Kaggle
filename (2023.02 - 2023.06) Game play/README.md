# File Description
```
├── kaggle/input
│   ├── predict-student-performance-from-game-play
│   └── game-play-train-parquet_pre_2
├── model_v3
│   ├── importance_dict.pkl
│   ├── XGB_question1.xgb
│   ├── XGB_question2.xgb
│   ├── ...
│   └── XGB_question18.xgb
├── Train_code_one_xgboost_v6_cv070030-LB-calculate.ipynb
└── inference_code_lb-0-706-catboost-mix-xgboost-lgbm.ipynb

```

# Summary

- **주제**
    - Predict Student Performance from Game Play
- **목표**
    - 게임 기반 학습 중 학생의 성과를 실시간으로 예측하는 것
    - 가장 큰 규모의 공개 게임 로그 데이터 세트 중 하나를 기반으로 학습된 모델을 개발
- **평가 지표**
    - F1 score
- **핵심 전략**
    - Feature Engineering
    - Using the old level feature
    - When predicting question i, use the value of predicting question <i-1 as a feature
- **앙상블:** 다음 3가지 모델을 앙상블하여 최종 결과 도출
    - Single XGBoost model
    - Single LGBM model
    - Single Catboost model

# More Detail
https://steadfast-shaker-35b.notion.site/2023-02-2023-06-Game-play-66363076f8054e6b80cf68b0cb0bd351?pvs=4
