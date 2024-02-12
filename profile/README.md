<div align="center">
  <h1>Mong Mong Village : 멍멍빌리지
  <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Felice-final-team6&count_bg=%23FFD100&title_bg=%23555555&icon=datadog.svg&icon_color=%23FFD100&title=hits&edge_flat=false"/></a></h1>
</div>

![mongmong](https://github.com/elice-final-team6/MongMongVillage-FE/assets/33516975/42de15ba-cd42-441d-9bd7-632f2b9570da)

에견인들을 위한 커뮤니티와 서울의 애견카페 리뷰 및 정보공유 사이트<br/>
엘리스 SW트랙 6기 최종 팀프로젝트 최우우상🏅수상

## 개발기간 
2023.11 ~ 2023.01

## 배포주소
https://www.mongmongvillage.store/

## 테스트 계정
```
- 일반유저
ID : elice1@test.com
PW : 11111111

- 관리자 ( 모든 게시글,리뷰,댓글 삭제 가능)
ID : admin@mongmong.com
PW : adminpw1234
```

## 개발환경
- 프론트엔드 
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=React&logoColor=white) <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/> <img src="https://img.shields.io/badge/-styled_components-DB7093?style=flat-square&logo=styled-components&logoColor=white" alt="Styled-Components"/> <img src="https://img.shields.io/badge/-React_Query-FF4154?style=flat-square&logo=react-query&logoColor=white" alt="React Query"/>
- 백엔드
<img src="https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js"/> <img src="https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"/> <img src="https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx"/> <img src="https://img.shields.io/badge/-PM2-2B037A?style=flat-square&logo=pm2&logoColor=white" alt="PM2"/> <img src="https://img.shields.io/badge/-Amazon_S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white" alt="Amazon S3"/>
- 협업 
![GitHib](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=GitHub&logoColor=white) ![Notion](https://img.shields.io/badge/-Notion-black?style=flat-square&logo=Notion&logoColor=white) ![Pigma](https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white)


## 팀원구성 및 역할
| 이름   | 구분              | 주요 역할     |
|--------|------------------|----------|
| [최정윤](https://github.com/cjy00n) | 팀장             | 전체 프로젝트 관리, 프론트엔드 |
| [김영욱](https://github.com/yeonguk0201) | 팀원    | 프론트엔드  |
| [이윤경](https://github.com/ktoo23) | 팀원           | 백엔드  |
| [이지형](https://github.com/j-h-711) | 팀원  |  프론트엔드        |
| [임가림](https://github.com/galimii) | 팀원  |  백엔드        |


## 화면 구성 
- 반응형 웹을 적용하여 태블릿 및 모바일 환경에서는 다르게 보일 수 있음

| 메인 페이지                           | **커뮤니티** 목록 / 상세 페이지                         | **카페** 지도/리스트/상세 페이지                         |
|---------------------------------------|------------------------------------------|------------------------------------------|
|![main](https://github.com/elice-final-team6/.github/assets/33516975/5f487377-36c1-4e74-8102-d5309017b069)| ![community](https://github.com/elice-final-team6/.github/assets/33516975/0aaadb95-6e83-4f67-9897-2cfa073a4ae3)| ![cafe](https://github.com/elice-final-team6/.github/assets/33516975/2ee0ad84-6c8f-498e-a1e6-e3b02a63946b)|

|**리뷰** 목록/상세 페이지                           | 로그인 / 회원가입 페이지                         | 마이페이지 / 내활동 페이지                         |
|---------------------------------------|------------------------------------------|------------------------------------------|
|![review](https://github.com/elice-final-team6/.github/assets/33516975/8c553cd9-1e2a-4050-9bc8-d66a59b0e413)| ![auth](https://github.com/elice-final-team6/.github/assets/33516975/da6148da-27c9-41af-847a-834e987b576b)| ![my](https://github.com/elice-final-team6/.github/assets/33516975/3fb83397-810e-4cfd-825e-71b164e14a5b)|


## 주요 기능
| 섹션        | 기능                                      | 섹션          | 기능                                          |
|-------------|-------------------------------------------|---------------|-----------------------------------------------|
| **메인페이지**  | 1. 배너이미지 자동 슬라이드                 | **커뮤니티**     | 1. 카테고리 별 필터링                            |
|             | 2. 애견카페 검색 이동                        |               | 2. 인기순 / 최신순 sorting                      |
|             | 3. 인기 애견카페 추천                        |               | 3. 검색 기능                                   |
|             | 4. 인기글 추천                             |               | 4. 페이지네이션                                |
|             |                                           |               | 5. 게시글 작성 / 수정 / 삭제 기능                |
|             |                                           |               | 6. 댓글 작성 수정 / 삭제                        |
|             |                                           |               | 7. 좋아요 기능                                 |
| **카페**      | 1. 카페 지도 검색                          | **리뷰**        | 1. 리뷰 작성  (별점 매기기) / 수정 / 삭제       |
|             | 2. 전체 카페 리스트                         |               | 2. 별점 높은 순 / 최신순 sorting                |
|             | 3. 카페 상세 정보                          |               | 3. 페이지네이션                                |
|             | 4. 카페 별 리뷰 모아보기                    |               | 4. 같은 카페의 리뷰 모아보기                    |
|             | 5. 별점 계산                               |             |                                           |
| **회원가입**  | 1. 아이디 및 닉네임 중복확인               | **마이페이지**   | 1. 내 정보 수정 (프로필사진, 닉네임, 소개글)     |
|             | 2. 비밀번호 일치 확인                      |               | 2. 내 활동 모아보기 (작성글, 작성댓글, 좋아요, 작성리뷰) |
|             | 3. 약관 확인 창                           
| **헤더 / 푸터**  | 1. 네비게이터                                 |

## 시연 영상 
[![Youtube Badge](https://img.shields.io/badge/Youtube-ff0000?style=flat-square&logo=youtube&link=https://www.youtube.com/c/kyleschool)](https://youtu.be/3BLg_u27zXw)

