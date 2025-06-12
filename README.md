# STAYPICK
> 실사용 숙소 예약 플랫폼 (풀스택 팀 프로젝트)

![Tech Stack](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) 
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=spring-boot&logoColor=white) 
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)

---

##  프로젝트 소개  
STAYPICK은 사용자가 숙소를 검색하고 객실을 선택해 예약 및 결제를 진행할 수 있는 실시간 숙소 예약 플랫폼입니다.  
리뷰 작성, 마이페이지 예약 내역 확인, 관리자 기능(예약 관리, 리뷰 관리, 요금 설정 등)까지 통합된 서비스를 목표로 개발되었으며,  
React와 Spring Boot 기반의 RESTful 구조로 사용자와 관리자 양쪽의 UX를 모두 고려해 설계되었습니다.

---

##  개인 기여도

**기획, UI/UX 설계 및 디자인, 프론트엔드 구현, 백엔드 구현 및 API 절반 이상, 배포 환경 구성까지 프로젝트 전반을 주도적으로 수행.**

- 전체 서비스 흐름 및 기능 명세 작성, Figma 기반 와이어프레임 및 UI 설계.  
- 사용자 주요 화면 레이아웃 구성 및 UX 흐름 직접 설계 (검색 → 예약 → 결제 → 마이페이지).  
- React 기반 사용자 기능(예약, 결제, 마이페이지) 구현 및 상태 관리.  
- 관리자 페이지(예약 관리, 리뷰 통계, 요금 설정 등) UI 및 프론트엔드 로직 구현.  
- Spring Boot 기반 백엔드 로직 절반 이상 구현 (예약, 리뷰, 결제, 인증 등 핵심 API 포함).  
- 정적 이미지 서빙 처리, MySQL 기반 DB 테이블 설계 및 연동.  
- AWS EC2 서버 환경 구성, S3 연동 등 배포 준비.

---

## 기술 스택

| 분류       | 기술 |
|------------|-----------|
| **Frontend** | React, JavaScript (ES6), HTML5, CSS3, Bootstrap |
| **Backend**  | Java, Spring Boot, MySQL, JWT, REST API |
| **DevOps**   | AWS EC2, RDS, S3 |
| **Tools**    | GitHub, Postman, Figma, VSCode |

---

##  주요 기능

### 사용자
- 로그인,회원가입(kakao, naver 로그인, 회원가입도 같이 구현)
- 숙소 검색, 지역/유형 필터링
- 조건 통과 가능한 숙박일 / 인원 설정
- 숙소 상세 정보와 이미지,객실정보 출력 구현
- 숙소리뷰, 숙소문의모달, kakaomap지도 기능 구현
- Toss Payments API 테스트용 결제 가능
- 마이페이지: 예약 내역 조회, 리뷰 작성,문의 조회, 내 정보 조회 및 변경

### 관리자
- 달력 컴포넌트를 활용한 메인 대시보드 관리(예약리스트,예약정보,리뷰,퀵메뉴 포함)
- 예약 내역 관리 (상태/기간/조건 필터링)
- 객실 상태 관리 (객실 마감,열기 기능)
- 숙소 정보,객실 정보 수정 및 관리
- 성수기 및 주말 기간 요금 설정 및 관리
- 객실 기본요금 설정 및 관리
- 할인 판매 설정 관리
- 리뷰 목록 조회 및 관리 기능
- 문의 관리 기능

---

## 주요 화면

| 사용자 예약 화면 | 관리자 화면 |
|------------------|----------------|
| ![사용자 예약 화면](./images/reservation.png) | ![관리자 화면](./images/admin.png) |

---

## 진행 상황

- [x] 사용자 기능 및 관리자 페이지 기능 구현 완료
- [x] 프론트/백엔드 연동 완료
- [ ] AWS 배포 환경 구성 예정

---

## 🔗 관련 링크

- 프로젝트 GitHub: [https://github.com/yourid/staypick-summary](https://github.com/yourid/staypick-summary)  
