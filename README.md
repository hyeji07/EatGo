# 👨‍🍳 Eat Go

## 프로젝트 소개
레스토랑 앱 React TDD 프로젝트입니다.<br />
API를 이용하여 레스토랑을 조회하고 리뷰를 남길 수 있는 앱을 구현하였습니다.<br />
지역과 음식 종류를 선택하면 레스토랑이 출력되며, 해당 리뷰와 평가를 확인하고 직접 리뷰를 남길 수 있습니다.<br />
리덕스 툴킷을 사용하였으며, Emotion을 이용해 앱을 꾸몄습니다.<br />
UseCallback과 React.memo를 이용해서 성능을 최적화하였습니다.

## URL
https://anne-eatgo.netlify.app

## 프로젝트 기간
2022.11.14 - 2022.12.04

## 사용기술
React, Redux, Jest, Emotion,
React Testing library
<br /><br /><br />

## 주요기능
### 🙍‍♂️ Login
API 통신으로 accessToken을 전달받아 저장된 사용자 정보로 로그인을 하면, 리뷰를 남길 수 있습니다. 
![login](https://user-images.githubusercontent.com/108104436/208664508-e82bb8d7-be4b-483a-bc9a-1d821d98b965.png)
▲ Login
<br />
![logout(login된상태)](https://user-images.githubusercontent.com/108104436/208664525-000d7de0-9e96-4658-b970-f73f76470862.png)
▲ Logout

<br /><br />

### 🍴 레스토랑 조회
Restaurants Page에서 지역과 음식 종류를 선택하면 아래에 해당하는 레스토랑이 출력됩니다.<br />
레스토랑을 누르면 해당 리뷰와 평가를 확인할 수 있습니다.
![restaurants](https://user-images.githubusercontent.com/108104436/208665516-427855ec-336f-480e-8b7a-33dc1425284f.png)

<br /><br />
### ⭐ 리뷰 확인 및 작성
레스토랑을 누르면 해당 정보와 리뷰를 볼 수 있습니다.<br />
로그인을 했을 경우에만 리뷰를 작성할 수 있으며, '리뷰 남기기' 버튼을 클릭 시 API를 통해 리뷰가 반영됩니다.
![restaurant(restaurants_result)](https://user-images.githubusercontent.com/108104436/208667753-807eff89-8209-4c10-b015-ad8a173d9a1a.png)

<br /><br />
### 🔺 Not Found Page
잘못된 URL일 경우 NotFound Page로 연결됩니다.
![notfound](https://user-images.githubusercontent.com/108104436/208667190-ef095c76-7395-4ba3-a166-bf2286cdfcaa.png)


<br /><br />
## ⚙ 참고
### 🔐 Login 정보
id : tester@example.com <br />
password : test

<br /><br />
### 설치하기

```bash
npm install
```

### 실행하기

```bash
npm start
```

