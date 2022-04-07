# 🎈프로젝트 소개
문서가 회전되어 있는 경우에 OCR 성능이 낮아집니다.   
문서 이미지의 각도를 예측하여 회전 보정을 통해 OCR 성능을 높이는 프로젝트입니다.

![image](https://user-images.githubusercontent.com/74346889/162189274-59db6b9d-0096-48c2-a2bf-aa5a322051e2.png)

# 📑데이터 소개
* ### **Train data** : 인공 합성 데이터 
     
![image](https://user-images.githubusercontent.com/74346889/162192208-f715d1bf-5e52-4bdb-9cfc-4944483a81e3.png)
![image](https://user-images.githubusercontent.com/74346889/162192242-eaf78396-7007-47d2-8c86-641cc7302130.png)
* ### **test data** : 실제 데이터  
  
![image](https://user-images.githubusercontent.com/74346889/162192843-7265bbb4-d814-4905-986c-77747df875f1.png)






# 프로젝트 순서
1. 로민에서 제공받은 데이터를 1도씩 틀어 360도의 사진 저장.
2. 모델 성능을 높이기위해 이미지 증식 후 vgg16모델 전이학습.
3. 몇 블록을 동결해야 가장 높은 성능이 나오는지 확인.
4. 모델 성능을 쉽게 보기위해 시각화.
5. 모델 사용

# 후기 
문서 이미지의 각도를 예측하는 하는데 실패ㅠㅠ..
이미지에 비해 너무 많은 레이블이 있는 것이 실패의 큰 요인중 하나라고 생각한다.   
각도 예측을 할 때 딥러닝을 포함해서 총 3가지 방법을 생각해냈다.
+ ### minAreaRect() 함수를 통해 각도 예측   
![image](https://i2.wp.com/theailearner.com/wp-content/uploads/2020/11/movie1-1.gif?resize=600%2C600&ssl=1)   
+ ### 

