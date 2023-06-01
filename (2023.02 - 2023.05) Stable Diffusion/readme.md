# 2023-Kaggle
## Competition: Stable Diffusion - Image to Prompts
* **Competition Subject**: Deduce the prompts that generated our "highly detailed, sharp focus, illustration, 3d renders of majestic, epic" images
    * Link: https://www.kaggle.com/competitions/stable-diffusion-image-to-prompts
* **Inference Code**: final-clip-knnregression-clip-vit-clip22.ipynb
## 팀원 및 대회 결과

**junseonglee11 :**  [https://www.kaggle.com/junseonglee11](https://www.kaggle.com/junseonglee11)

**Ayaan Jang     :**  [https://www.kaggle.com/ayaanjang](https://www.kaggle.com/ayaanjang)

**결과:** 68 위 / 1231 팀 ( 🥉Bronze medal, 상위 6%)

## Summary
![Untitled](https://github.com/ehdgnsdl/2023-Kaggle/assets/87434001/83d1d45b-aace-476f-bb47-271e2cd1f121)
Prompt Prediction Challenge: An Overview of the Complete Process

- **주제**
    - Stable Diffusion - Image to Prompts
- **목표**
    - 생성된 이미지가 주어진 텍스트 프롬프트를 예측할 수 있는 모델을 만드는 것.
    - 잠재 관계가 얼마나 가역적인지 이해하기 위해 Stable Diffusin 2.0에서 생성된 다양한 (prompt, image) 쌍이 포함된 데이터 세트에 대한 예측을 수행
- **평가 지표:** 예측된 프롬프트 임베딩 벡터와 실제 프롬프트 임베딩 벡터 사이의 평균 코사인 유사도(the mean [cosine similarity](https://en.wikipedia.org/wiki/Cosine_similarity) ) 점수.
- **앙상블:** 다음 5가지 모델을 앙상블하여 최종 결과 도출
    - ViT-G-14 (kNN regression)
    - ViT-H-14 (kNN regression)
    - Clip-ViT-large-patch14
    - Clip-ViT-large-patch16_384
    - CLIP+BLIP (CLIP interrogator)

## Subject
- 생성된 이미지가 주어진 텍스트 프롬프트를 예측할 수 있는 모델을 만드는 것.
- 잠재 관계가 얼마나 가역적인지 이해하기 위해 Stable Diffusin 2.0에서 생성된 다양한 (prompt, image) 쌍이 포함된 데이터 세트에 대한 예측을 수행

## More Detail
https://steadfast-shaker-35b.notion.site/2023-02-2023-05-Stable-Diffusion-12636c2cf761471085c1dfd4129da01c
