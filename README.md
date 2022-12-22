# 한국어 감정 분류 모델


## 학습 데이터 구축

 - AI Hub의 '한국어 감정 정보가 포함된 단발성 대화 데이터셋' 활용
 - 긍정적 감정과 부정적 감정의 균형을 맞춘 학습 데이터를 구축함 
 - 긍정: 기쁨/신뢰/기대, 중립, 부정 : 슬픔/분노/혐오
 

##  모델 학습

 - 한국어 위키피디아에서 약 500만 개의 문장과 5,400만개의 단어를 학습시킨 KoBERT를 활용
 - [code](https://github.com/youngsilpark/Korean-Emotion-Classification/blob/main/emotion_classification.ipynb)
 

## 예측

 - [AI Hub의 '온라인 구어체 말뭉치 데이터' 활용](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=625)
 - 온라인 영상 댓글의 카테고리 별 감정 분석을 진행함

 - 결과
 
![image](https://user-images.githubusercontent.com/107041027/209046776-b8da9d50-1a3d-4b4e-b11c-b2dd1be83da0.png)
![image](https://user-images.githubusercontent.com/107041027/209046715-24d50b4a-c9bb-4f35-99d6-ed488e1728a7.png)


## Reference

 - [SKTBrain/KoBERT](https://github.com/SKTBrain/KoBERT)
 - [AI Hub](https://aihub.or.kr/)
