데이터 셋 준비
 1. preprocessing폴더에 wav 파일들을 분류해서 넣고 prepocessing.ipynb(또는 prepocessing_random.ipynb)을 사용해  2초 단위 (또는 1~3초 단위)로 잘라 unsplit폴더에 저장됨
 2. unsplit에 2초 (또는 1~3초) 단위로 잘려진 tensor들을 기본적으로 0.9 대 0.1 비율로 (shuffle 적용) eval 폴더와 train 폴더에 저장 (데이터 불균형을 해소하기 위해 가장 적 은 데이터 셋 크기만큼 나머지 데이터셋 크기도 맞춤
 3. (random 붙은건 1~3초 단위로 훈련시키거나 데이터 셋 준비를 그렇게 했거나)
swishnet_times_0_epoch_410(random).pth 은 1~3초 단위로 훈련 시킨 모델


훈련
 1. train.ipynb으로 진행

테스트
 2. test.ipynb에서 진행, 1~3초 단위로 추론
 (swishnet_times_0_epoch_410(random).pth)
 
