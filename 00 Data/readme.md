# Pronunciation error detection Model의 학습을 위한 Dataset
- 01 Sound(MFCC): 학습용 음성 데이터를 MFCC 샘플링을 통해 추출한 값
 - { 파일명 : 음성 Feature } 형태의 Dictionary 형태의 pickle들이 저장
- 02 text: 학습에 사용되는 음성 데이터에 대응되는 텍스트 데이터
 - { 파일명 : 텍스트 } 형태의 Dictionary 형태의 pickle들이 저장
- 03 textToVector: 학습에 사용되는 text를 vector화(정수화)하는 클래스
 - pickle 형태로 저장
