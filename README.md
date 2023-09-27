# Peoplancer
프리랜서와 기업 간의 효율적인 매칭을 목적으로 하는 웹사이트 입니다.

## 🕰️개발 기간
* 23.04.18 - 23.06.09 ( 총 53일 )

### ⚙️ 개발 환경 및 사용 기술 스택
* **개발 환경(Environment)**
  * JDK 17
  * Mysql 8.0
  * STS 4.18
  * Vscode 1.82.1
* **사용 기술 스택(Technology Stack)**
  * Mybatis
  * HTML
  * React
  * CSS
  * JavaScript
  * Stomp

## 📌 주요 기능
**1:1 DM -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%EC%A7%80%EB%8F%84-(-Map-)-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* WebSocket 기반의 Stomp 라이브러리 활용한 실시간 채팅
* DB와 연동하여 상대방의 상세정보 및 평균 평점 표시
* 이미지, 파일 업로드 기능
* 채팅방 나가기 기능

**프로젝트 , 프리랜서 게시판 -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%EC%97%AC%ED%96%89%EC%B6%94%EC%B2%9C-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* 게시판 기능
* 추천 기능 및 관심목록 저장 기능
* 1:1 DM으로 연결 및 마이페이지의 달력 API로 연결
* 게시글 CRUD
* 게시글 검색 기능
* 리뷰 CRUD
* 별점 기능
* 태그를 활용한 효율적 매칭 기능
  
**로그인 -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* DB값 검증
* 로그인 시 쿠키 및 세션 생성

**회원가입 -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* ID 중복 체크
* 회원 유형 (기업, 개인) 선택

**마이페이지 -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* 진행 중인 프로젝트, 지원한 프로젝트, 관심 프로젝트 현황 확인 기능
* 달력 API를 활용하여 원하는 날짜에 일정 등록 및 확인 기능
* ~~이력서 및 라이센스 파일 관리~~
* 회원정보 수정 및 탈퇴

**고객센터 -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%EA%B4%80%EB%A6%AC%EC%9E%90%ED%8E%98%EC%9D%B4%EC%A7%80-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* 자주하는 질문
* 1:1 문의 CRUD

**관리자 페이지 -** **[상세보기 - Wiki 이동](https://github.com/dlrdyd97/Petopia_BE/wiki/%EA%B4%80%EB%A6%AC%EC%9E%90%ED%8E%98%EC%9D%B4%EC%A7%80-%EA%B8%B0%EB%8A%A5-%EC%86%8C%EA%B0%9C-(-BE-))**
* 모든 프로젝트의 시작/마감일 통계
* 프로젝트의 현재 상태 ( 모집중 / 모집완료 / 진행중 / 진행완료) 통계
* 프로젝트의 요구 기술 및 프리랜서의 보유 기술 통계
* 월별 회원 가입 증감 / 1:1 문의 답변/ 미답변 통계
* 회원 상세정보 및 수정
