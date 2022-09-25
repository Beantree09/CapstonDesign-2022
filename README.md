# CapstonDesign-2022
Yeungnam Univ. 2022 CapstonDesign

2022 영남대학교 캡스톤 디자인 독거노인 돌보미 로봇 "보미"에 탑제되는 Software

<br/>

## Init
- JetsonNano : 
  mobilenet_ssd_v2 를 이용한 Tracking 모듈과 tensorflow lite 버전의 학습 모듈을 통해 Human_Tracking 제작, JetsonNano에 탑제해 기능 구현.
  
- RaspberryPi
  fer2013.csv 데이터셋을 활용해 기계학습하여 Emotion_Recognition모듈을 제작. RaspberryPi에 탑제해 기능 구현.
  GoogleAssistant를 활용한 음성인식 모듈을 제작,  RaspberryPi에 탑제해 기능 구현.
  얼굴인식 모듈과 음성인식 모듈의 감정Score를 계산하여 Feedback을 출력해주는 Master모듈 제작.
  
<br/>

## 기능구현도

##
