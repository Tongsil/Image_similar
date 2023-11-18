# Image_similar


## **프로젝트 주제**

- 사전 학습된 keras 속의 CNN 모델을 이용하여 포켓몬의 유사도 구하기

## 데이터

- images: 포켓몬 이미지 809개 (png, jpg)
- pokemon.csv: 포켓몬 정보 (이름, 타입)

[Pokemon Image Dataset](https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types)

## 실행방법

- [ pokemon_list[] ]에 비교하고자 하는 포켓몬 번호 입력
- ex) 12번째 포켓몬 이미지 유사도 구하기
    - pokemon(PATHS[12], PATHS[0:809])
    - pokemon_result = pd.DataFrame(result, columns = [pokemon_list[12]])
    - 결과값 데이터프레임으로 확인가능
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/455459bb-3a46-447e-bfee-e53397ae9bee/2b5301a1-e046-411a-9bfe-852c2e12690c/Untitled.png)
