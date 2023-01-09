
## Goal
해당 프로젝트에서는 화장지의 현재 남아있는 량이 충분한지 부족한지를 분류하는 것을 목표로 하고 있습니다.

## 데이터

*   **train_data** - 학습에 사용할 직접 촬영한 화장지 데이터로 92개의 이미지와 직접 제작한 경계박스 영역정보를 포함합니다
*   **test_data** - 학습 데이터에 포함되어있지 않은 6개의 다양한 화장지 상태가 있습니다.


## 학습 데이터 미리보기

*   화장지가 부족한 상태와 부족하지 않은 상태 상태로 다중 분류를 진행합니다.
*   다음의 이미지는 순서대로 학습 데이터의 화장지가 부족하지 않은 상태와 부족한 상태의 예시입니다


![01 mp4_20221206_201245 268](https://user-images.githubusercontent.com/102031218/211231312-9c9b4e91-04ca-45de-a2d0-d0e9edbfc968.jpg)
![04 mp4_20221206_211319 751](https://user-images.githubusercontent.com/102031218/211231366-4a221752-9090-4e06-a780-358c959ec036.jpg)

## 결과
화장지의 상태를 Enough와 Not Enough로 분류합니다


![result1](https://user-images.githubusercontent.com/102031218/211232555-ba9d0fba-b9ed-4468-b06b-c438dbf8a6b8.jpg)
![result2](https://user-images.githubusercontent.com/102031218/211232558-38ad1744-3682-43cb-8d40-e07c2df7840b.jpg)
![result3](https://user-images.githubusercontent.com/102031218/211232561-6d5f2521-a459-417a-88e0-eb4de6b5c0b2.jpg)
![result4](https://user-images.githubusercontent.com/102031218/211232565-8d44acf9-ffaf-44f5-ad9e-109c9e7ad013.jpg)
