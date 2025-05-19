데이터 셋 준비
1. preprocessing폴더에 wav 파일들을 분류해서 넣고 prepocessing.ipynb(또는  prepocessing_random.ipynb)을 사용해  2초 단위 (또는 1~3초 단위)로 잘라 unsplit폴더에 저장됨
2. unsplit에 2초 (또는 1~3초) 단위로 잘려진 tensor들을 기본적으로 0.9 대 0.1 비율로 (shuffle 적용) eval 폴더와 train 폴더에 저장 (데이터 불균형을 해소하기 위해 가장 적은 데이터 셋 크기만큼 나머지 데이터셋 크기도 맞춤

훈련
1. train.ipynb으로 진행

테스트
2. test.ipynb에서 진행, 1~3초 단위로 추론
 
