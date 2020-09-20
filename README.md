# [한이음2018 공모전] 지하철 기반 최적의 약속 장소 및 주변 힙플레이스 추천 서비스

Recommendation of appointment location using big data and recommendation of surrounding hip place

### 프로젝트 기간 

2018.04.24 ~ 2018.11.30(7개월)

### 개발환경

- HTML + JavaScript + jQuery + ajax
- Java + Mysql
- Mapbox API + 공공데이터 포탈 API + kakao 좌표 변환 API + 서울관광공사 API

### 팀 정보

IOI(IT + Occure + Influence: 아이티에 영향력을 일으킨다.) 
- 정다희: 프로젝트 관리, 서버 관리, 백엔드 구현, 데이터베이스 구축
- 이미지: MapboxAPI 활용, 프론트엔드 구현
- 이유리: 프론트엔드, API 및 라이브러리 탐색
- 김예준: 화면 디자인 및 목업 

### 작품명

sai (너와 나의 사이, 우리의 사이)

### 작품 소개

본 서비스는 최적의 약속 장소를 추천해주는 서비스로, 만남이 실질적으로 이루어질 수 있는 중간지점을 제공할 뿐만 아니라, 지하철의 이동시간을 계산하여 공평한 중간장소를 제시함. 이에 그치지 않고 그 지점 주변의 놀거리와 카테고리별 힙플레이스 등을 보여주는 서비스임. 선택된 장소까지의 최소 환승 경로와 최단 거리 경로를 지도에 표시해줌으로써 편리하게 서비스를 이용할 수 있도록 편의성을 제공할 수 있음.

### 전체적인 구성도(S/W, H/W)

<img width="629" alt="Screen Shot 2019-11-16 at 5 10 52 PM" src="https://user-images.githubusercontent.com/33794732/68990264-8f43f900-0894-11ea-9b99-78a66e539d54.png">

### 전체적인 서비스 흐름도 

<img width="915" alt="Screen Shot 2019-11-16 at 5 11 27 PM" src="https://user-images.githubusercontent.com/33794732/68990265-8f43f900-0894-11ea-82a8-622af98b8d57.png">

### 작품의 개발배경 및 필요성

기존에 있는 서비스의 경우 좌표상의 중간 지점을 알려주기 때문에 실질적으로 만남이 불가능한 장소(산 또는 강 한 가운데)를 추천해주는 경우가 많음. 따라서 실질적인 만남이 이루어질 수 있는 장소와 인근 힙플레이스 정보를 제공바등ㄹ 수 있다면 편리할 것으로 전망함.

### 작품의 특장점

스마트폰과 컴퓨터를 사용하여 서비스를 이용할 수 있는 반응형 웹으로 구현하여 보다 편리하게 서비스를 이용할 수 있도록 하였음. 디바이스에 맞게 사용할 수 있어 언제 어디서든 최적의 중간 지점을 서비스 받을 수 있고 누구에게나 공평한 중간지점을 추출해주기 때문에 실질적인 만남이 이루어질 수 있음. 좋아요 기능을 통해 장소나 추억을 기록할 수 있으며, 사용자에게 적절한 힙플레이스를 추천해줌

### 작품 기능

* 중간지점 분석 알고리즘: 실제 소요시간(대중교통 이용)을 고려하여 여러명에게 최적의 중간지점을 분석하여 추천
* 힙플레이스 추천: 빅데이터를 활용하여 저장되어 있는 최적의 장소 추천 시스템을 제공
* 경로: 최적의 중간 지점까지 가는 경로를 최소 환승, 최단 경로로 표시해서 사용자에게 편의성 제공
* 코스 추천: 중간 지점 분석 알고리즘에 참여한 사용자들의 선호도를 기반으로 코스를 추천하여 활용성 향상
* 반응형 웹: 어떠한 디바이스에서 서비스를 요청하더라도 화면 크기에 알맞게 서비스를 제공

### 작품의 기대효과 및 활용분야

작품의 목적인 약속시간을 잡는 데에 시간을 절약할 수 있으므로 실생활에 도움을 줄 수 있는 프로젝트로 기대됨. 상용화 될 가능성이 높고 빅데이터 활용을 통한 추천 시스템이므로 다른 분야에서도 유사 서비스로 확장 가능

### Screenshots

<img width="270" alt="Screen Shot 2019-12-01 at 6 05 04 PM" src="https://user-images.githubusercontent.com/33794732/69911886-4fb90780-1465-11ea-8736-14b0e00fc773.png">
<img width="267" alt="Screen Shot 2019-12-01 at 6 05 15 PM" src="https://user-images.githubusercontent.com/33794732/69911887-4fb90780-1465-11ea-8746-230b254e315e.png">
<img width="269" alt="Screen Shot 2019-12-01 at 6 05 30 PM" src="https://user-images.githubusercontent.com/33794732/69911888-4fb90780-1465-11ea-8a3d-f6607c5d419b.png">


### Video link
동영상: https://www.youtube.com/watch?v=_PFxNS8p6PI&t=3s

