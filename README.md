# 알바로그 (Node.js)

## ⏳기간

### 2021.04 ~ ing

## 😀 스토리

아르바이트를 진행하면서 사장님들과 알바생들 사이에서 일어날수 있는 모든 Issue를 관리해주는 웹 애플리케이션을 만들고자 진행되는 프로젝트입니다. 제가 발표했던 아이디어는 아니였지만 저도 알바를 정말 많이 해봐서 너무나도 괜찮은 주제라고 생각하게되어 팀원으로써 참여하게되었습니다.

## 🌐 [웹페이지](https://dashboard.heroku.com/apps/albalog-test) (Baek-End)

## 🙋‍♂️ Github

[AlbalogTeam](https://github.com/AlbalogTeam)

## 🎲 역할

- Back-End
- Resolve Git and Github Issue

## ⚒️ 기술스택

- Node.js
- Express
- MongoDB
- mongoose

## ☘️ Package.json

```jsx
{
  "name": "albalogserver",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "babel-node index.js",
    "dev": "nodemon --exec babel-node index.js"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/godtaehee/AlbalogServer.git"
  },
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/godtaehee/AlbalogServer/issues"
  },
  "homepage": "https://github.com/godtaehee/AlbalogServer#readme",
  "dependencies": {
    "@babel/core": "^7.14.0",
    "@babel/node": "^7.13.13",
    "@babel/preset-env": "^7.14.0",
    "@sendgrid/mail": "^7.4.4",
    "bcryptjs": "^2.4.3",
    "cors": "^2.8.5",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.12.7",
    "morgan": "^1.10.0",
    "validator": "^13.6.0"
  },
  "devDependencies": {
    "nodemon": "^2.0.7"
  }
}
```

## ❗ 프로젝트 진행

- [0주차](https://www.youtube.com/watch?v=A76W9kts5u4) - 오리엔테이션 & 팀 빌딩

    개발자의 품격님이 임의로 지정해주신 팀원을 바탕으로 오리엔테이션을 진행하였습니다.

- [1주차](https://www.youtube.com/watch?v=JmbHsfjhjSY&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=3) - 아이템 선정 및 발표

    저희 팀은 각자 해보고싶은 아이디어를 발표했고 그중에 아르바이트생과 사장님 사이에서 일어날수있는 다양한 이슈를 관리해주는 웹 애플리케이션을 만들고자 했습니다

- [2주차](https://www.youtube.com/watch?v=UmeayBglVwM&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=4) - 벤치마킹

    [벤치마킹.key](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5.key)

    국내 14개, 해외 2개를 벤치마킹하여 각각의 사이트가 어필하는 기능과 디테일한 기능까지 모두 조사하여 비공개 Google Sheet에 공통된 기능을 정리하고 새로운 기능까지 정리하여 저희 웹 애플리케이션의 기능을 구현하는데 있어서 많은 참고를 할수 있었습니다. 2번째 컬럼에 기능별로 중요도를 설정하여 A인 기능 우선으로 기능구현을 하기로 했습니다.

    ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.16.57.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.16.57.png)

- [3주차](https://www.youtube.com/watch?v=SKp-M7y54rc&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=4) - 사용자 분석 및 기능 설계

    ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.22.35.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.22.35.png)

    저희 서비스의 사용자는 매장관리와 아르바이트생 관리가 힘든 모든 자영업 사장님을 대상으로 하고있으며 앞서 벤치마킹했던 내용을 토대로 마인드맵으로 기능들을 구체화 했습니다. 이러한 기능설계를 함에있어서 벤치마킹했던 내용이 크게 도움이 되었습니다.

- [5주차](https://www.youtube.com/watch?v=htXO6oxzgBM&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=5) - Wireframe 설계

    카카오 오븐을 통해 저희 팀은 3주차의 기능설계 마인드맵을 토대로 분담하여 Wireframe을 작성했습니다. 다음은 제가 맡은 공지사항과 업무 메뉴얼의 Wireframe 입니다.

    - PC버전 - 공지사항, 업무메뉴얼

        ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.35.39.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.35.39.png)

        ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.35.49.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.35.49.png)

    - 모바일버전 - 공지사항, 업무메뉴얼

        ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.36.51.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.36.51.png)

        ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.37.04.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.37.04.png)

- [6주차](https://www.youtube.com/watch?v=JAeF2zukJYA&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=6) - UI 구현

    프론트분들이 React를 사용하여 화면구현을 하셨습니다. Wireframe에 있는 그대로 구현을 하셨고 추후 백엔드와 합치면서 변경사항이 생기면 프론트와 백엔드 모두 변경사항을 적용해서 변경될 예정입니다.

    [4조 - UI.pdf](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/4_-_UI.pdf)

- [7주차](https://www.youtube.com/watch?v=sZYyuJStlqA&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=7) - 데이터베이스 설계

    백엔드 3명이서 같이 디비설계를 하고 매주 피드백을 품격님께 받아서 업데이트 하거나 개발 도중 발생한 이슈에 따라 수정했습니다.

    ![%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.32.44.png](%E1%84%8B%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A1%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%20(Node%20js)%20d8ef4b53f0654390a17ed615190fd9e5/_2021-06-17__11.32.44.png)

- [8주차](https://www.youtube.com/watch?v=lHbe_nmVMPI&list=PLqbWuGdVBJd1bukVXopWjl5mUevBtj04h&index=8) - 구현 1주차
    - MongoDB를 사용하여 구현했습니다.
    - 관리자 회원가입
    - 매장 등록, 수정, 입장 (kakao 주소검색 api 이용)
    - 로그인 유지, 로그아웃 (access Token + LocalStorage)
    - 관리자 로그인
    - 직원 초대 기능 (이메일 전송 )
    - 공지 등록, 수정, 삭제, 리스트 (ckEditor5를 이용하여 글쓰기 구현)
    - 스케줄러 구현
    - 각 페이지 접근 권한 설정 ( 관리자만 입장가능, 직원만 입장가능, 미 로그인시 접속 불가능)
    - Category CRUD
    - Category 보여주는 방식에서 _id가 아닌 name으로 보여줘야하는 이슈 발생 및 해결
    - Notice CRUD
    - Notice Embeded in Location
    - WorkManual CRUD
    - WorkManual Embeded in Location
    - checkHasUserLocation 미들웨어 삭제

    - Category
        - ~~Category CRUD~~
        - ~~Category 보여주는 방식에서 _id가 아닌 name으로 보여줘야하는 이슈 발생 및 해결~~
    - Notice
        - ~~Notice CRUD~~
        - 
    - WorkManual
    - Transition
    - TimeClock
- 9주차 - 구현 2주차
