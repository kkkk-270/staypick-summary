# STAYPICK
> 실사용 숙소 예약 플랫폼 (풀스택 팀 프로젝트)

![Tech Stack](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) 
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=spring-boot&logoColor=white) 
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)

---

## 📌 프로젝트 소개  
STAYPICK은 사용자가 숙소를 검색하고 객실을 선택해 예약 및 결제를 진행할 수 있는 실시간 숙소 예약 플랫폼입니다.  
리뷰 작성, 마이페이지 예약 내역 확인, 관리자 기능(예약 관리, 리뷰 관리, 요금 설정 등)까지 통합된 서비스를 목표로 개발되었으며,  
React와 Spring Boot 기반의 RESTful 구조로 사용자와 관리자 양쪽의 UX를 모두 고려해 설계되었습니다.

---

## 📷 주요 화면

### 🧑 사용자 화면
| 검색 리스트 | 숙소 상세 | 결제 화면 | 토스 API | 결제 완료 |
|-------------|------------|-------------|---------------|----------------|
| ![user1](./images/user/user1.PNG) | ![user2](./images/user/user2.PNG) | ![user3](./images/user/user3.PNG) | ![user4](./images/user/user4.PNG) | ![user5](./images/user/user5.PNG) |

### 🛠️ 관리자 화면
| 대시보드 | 예약 관리 | 숙소/객실 관리 | 요금 설정 | 할인관리 |
|-------------|-------------|----------------------|---------------|--------------------|
| ![admin1](./images/admin/admin1.PNG) | ![admin2](./images/admin/admin2.PNG) | ![admin3](./images/admin/admin3.PNG) | ![admin4](./images/admin/admin4.PNG) | ![admin5](./images/admin/admin5.PNG) |

---

## 💡 주요 기능

### 사용자
- 로그인 / 회원가입 (Kakao, Naver 연동 포함)
- 숙소 검색 및 지역/유형 필터링
- 숙박일 및 인원 선택 기능 구현
- 숙소 상세 페이지: 이미지, 객실 정보, 리뷰, 문의 모달, KakaoMap 연동
- Toss Payments API를 활용한 테스트 결제 기능 구현
- 마이페이지: 예약 내역 조회, 리뷰 작성/수정, 문의 내역 확인, 회원 정보 수정 기능

### 관리자
- 달력 컴포넌트를 활용한 메인 대시보드 구성 (예약 리스트, 정보, 리뷰, 퀵메뉴 포함)
- 예약 내역 관리 (상태 / 기간 / 조건 필터링)
- 객실 상태 관리 (객실 마감/활성 전환)
- 숙소 및 객실 정보 수정
- 성수기 및 주말 기간 설정
- 객실 기본 요금 설정
- 할인 판매 설정 기능
- 리뷰 목록 및 통계 확인
- 사용자 문의 관리 기능

---

## 🛠 기술 스택

| 분류       | 기술 |
|------------|-----------|
| **Frontend** | React, JavaScript (ES6), HTML5, CSS3, Bootstrap |
| **Backend**  | Java, Spring Boot, MySQL, JWT, REST API |
| **DevOps**   | AWS EC2, RDS, S3 |
| **Tools**    | GitHub, Postman, Figma, VSCode |

---

## 🚧 진행 상황

- [x] 사용자 & 관리자 기능 구현 완료
- [x] 프론트/백엔드 API 연동 완료
- [x] AWS EC2 / S3 구성 완료 (배포 준비 중)


