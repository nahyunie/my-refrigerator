# <p align="center">머신러닝을 이용한 식재료 관리, 나의 냉장고</p>
<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/58367854/121835240-b205f000-cd0b-11eb-99c0-f18a74a12dac.PNG"/>
</p>

## 📖 프로젝트 소개

일반적인 가정집에는 냉장고가 필수적으로 사용된다. 하지만 어떤 식재료들이 냉장고에 있는지, 유통기한은 얼마나 남았는지 관리하는 것은 매우 번거롭다. 또한 유통기한이 넘도록 사용하지 않거나, 구비해놓고 소비할 방법을 몰라 낭비되는 식재료들도 허다하다. 
우리는 이러한 **식재료 관리의 문제**, **식재료 소비의 문제**를 해결하기 위한 해결책으로 **유통기한 관리와 사용자의 식재료를 바탕으로 레시피를 추천하는 어플**을 개발하였다.
<br>
<br>

## ✔ 주요기능

+ 회원관리
  + 회원가입
  + 로그인
  + 로그아웃

+ 식재료 관리
  + 식재료 추가
    + 카메라를 통한 자동 인식 추가
    + 식재료 리스트에서 검색하여 추가
   + 식재료 삭제
   + 식재료 유통기한 확인
   + 식재료 상세 영양정보 확인

+ 레시피 추천
  + 식재료 선택
  + 식재료 검색
  + 상세 레시피 확인

+ 알람
  + 유통기한 임박 알람

+ 냉장고 코드 관리
  + 냉장고 코드 복사, 변경, 초기화
  + 냉장고 코드 암호화, 복호화
<br>
<br>

## 📱 구성도
<p align="center">
  <img src="https://user-images.githubusercontent.com/58367854/121837294-29d61980-cd10-11eb-9774-5402d7b87d14.JPG"/>
</p>
<br>
<br>

## 💻 주요기술

| 기술 | 설명 | 개발툴 |
|---|:---:|---:|
| `Android` | 안드로이드 버전 9 이상을 타겟 | Android Studio |
| `Firebase` | Firebase Authentication으로 사용자 관리, Firestore에 식재료 저장 |  |
| `Tensorflow` | TensorFlow Object Detection API, MobileNet V2, transfer learning | Google Colab |
| `Web Crawling` | BeautifulSoup으로 이미지 데이터 셋 크롤링, JSoup으로 레시피 크롤링 |  |
| `AES-256` | AES 알고리즘으로 냉장고 고유코드 암호화, 복호화 |  |
| `개발언어` | java, python |  |
<br>
<br>

## 👩 💻 역할분담
| 기술 | 설명 |
|---|:---:|
| 진은혜 | 팀장, Tensorflow 모델 학습, android notification |
| 심정현 | Android UI Design, Firebase Database 관리 |
| 김수진 | Android UI Design, Android 모듈 구현 |
| 최나현 | Tensorflow 모델 학습, Firebase Authentication |
<br>
<br>

## 🎬 실행예시 
<img src="https://user-images.githubusercontent.com/58367854/122037724-d519c800-ce0f-11eb-816e-094e40c481b4.gif"/>
<br>
<br>

## 🎤 발표영상

youtube link 추가 예정
