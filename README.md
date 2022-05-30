# ICES-HomePage
ICES Lab. 을 대표하는 홈페이지를 제작합니다.


 > <https://ices-lab.github.io/ICES-HomePage/>


## 작업 규칙
 - **master에 직접 올리지 마세요 !**
 - **Force-commit 이나 hard 옵션 등을 사용하지 마세요 !**
 - **질문 및 건의사항은 슬랙을 적극 사용해주세요 ! :+1:**
 - 작업 branch는 feature/[이름약자]-[작업내용] 형태로 올려주세요. 
   - ex) feature/[TJ]-ProfilePage
   - **Branch 유지 기간은 일주일을 넘기지 마세요. (충돌방지)**
 - Commit Message는 한글로 최대한 자세히 적어주세요.
 - 작업물을 push 후에 pull requests를 진행해주세요.


## 작업 기간
### 📖 Gantt :fire:

```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section 버전관리
    AI 기술테스트  : a1, 2022-10-14, 10d
    가상 얼굴 학습 및 환경세팅  : 2022-10-14, 10d
    얼굴 인식 개선 및 적용 : after a1, 10d
    가상 얼굴 이미지 생성 및 분류 : after a1, 4d

    section Front-end
    와이어프레임     :a1,2020-10-14  , 10d
    react 학습 및 적용 : after a1,  10d
    사진 업로드 및 설정 기능 :after a1 , 10d

    section Back-end
    django 학습 및 적용 : a1,2020-10-14 , 10d
    회원기능      :a2,after a1 , 10d
    친구기능      :after a1  ,10d
    결과 이미지저장,공유  : a3,after a2, 2d
    스티커 기능  : a4,after a3, 2d
```
- 2022.05.23 ~ 2022.05.29 외관 보수 및 MEMBER 페이지 개발
  - [X] **개발환경 구축 및 버전 관리**
  - [X] 교수님 약력 및 수상 수집
  - [X] 박사과정 및 학부생 프로필 작성

## Installation
```
 > git clone https://github.com/ICES-Lab/ICES-HomePage.git

 > npm i
```


## Browsers support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Samsung |
| --------- | --------- | --------- | --------- | --------- | --------- |
| IE11, Edge| last version| last version| last version| last version| last version
