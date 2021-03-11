# CLOVA OCR 기반 한글데이터 훈련

> ## 환경
 |Option|Train_Select|
 |:---|:---|
 |Transformation|TPS|
 |FeatureExtraction|VGG|
 |SequenceModeling|BiLSTM|
 |Prediction|CTC|
 |imgH|100|
 |imgW|90|
 |charachter|가나다라마거너더러머버서어저고노도로모보소오조구누두루무부수우주바사아자배하허호국합육해공외교영사준외준영국기대표협정0123456789|

***

> ## 훈련 결과

 총 102개의 이미지를 대상으로 테스트 해보았음

 ### * 테스트 이미지 샘플
 ![11](https://user-images.githubusercontent.com/25381921/110720117-672e9500-8251-11eb-9483-47536e5a66e9.png)
 
 ### * 틀린 결과 이미지
 102개중 5개 이미지 오답
 
 ![11](https://user-images.githubusercontent.com/25381921/110720380-ca202c00-8251-11eb-9f33-a6ca3c7738d9.png)

 ### * 오류 발견
 predict 하는 두 파일에서 서로 결과가 다르게 나온다... 확인이 필요
 
 ![11](https://user-images.githubusercontent.com/25381921/110721299-9c3be700-8253-11eb-8749-d472eef6b31a.png)
