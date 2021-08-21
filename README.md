# fastCampus_DeepLearning_Study

 - fast company에서 진행하는 딥러닝 수업 정리.


# file infomation

 - [Deep_Learning_Study.pdf](Deep_Learning_Study.pdf) 
   - 3 - Ch 01. Tensorflow 2.0
   - 3 - Ch 02. Pytorch
   - 4 - Ch 01. Preprocess
   - 4 - Ch 02. Tensorflow 2.0 (~ 05)

 - [2021_08_07.ipynb](2021_08_07.ipynb)
   - 4 - Ch 02. 08.tit with tf.data
   - ~~4 - Ch 02. 09.callbacks - tensorboard - 2 ~~
   - 4 - Ch 02. 10.callbacks - tensorboard - 2
 - [2021_08_15.ipynb](2021_08.15.ipynb)
   - 4 - Ch 02. 12. callbacks - model checkpoint
   - 4 - Ch 02. 13. post process - history (결과 확인)
   - 4 - Ch 02. 14. post process - predict & predict_generator
   - 4 - Ch 02. 15. save and load model - h5

 - [2021_08_21.md](2021_08_21.md)
   - 5 - Ch 02. 01. (STEP 1) 얕은 신경망의 구조
   - 5 - Ch 02. 02. (STEP 1) 얕은 신경망을 이용한 분류와 회귀
   - 5 - Ch 02. 03. (STEP 2) 얕은 신경망의 수식적 이해

# 참고

## 구글드라이브 경로 마운트
```
!pip install unidecode # unidecode 패키지 다운로드

import unidecode

# Figure1 참고
# 이걸 실행하면 링크와 함께 무슨 authentication code를 넣으라고 칸이 뜬다.
# 링크 누르고 계정 엑세스 하는걸 허용해 준 다음 링크를 복사해서 칸에 입력하면 된다.
from google.colab import drive
drive.mount("/content/drive")
```

## m1 mac