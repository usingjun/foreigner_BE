# 🇰🇷 Kori: Global K-Culture Community & Chat
> **외국인들이 한국 문화를 배우고 한국인 친구를 사귈 수 있는 글로벌 커뮤니티 서비스**
> 2025년 8월 출시 이후 100여 개국 유저들이 활동 중이며, 약 3,000명의 유저가 함께하고 있습니다.

[![Google Play](https://img.shields.io/badge/Google_Play-Kori-green?style=for-the-badge&logo=googleplay)](https://play.google.com/store/apps/details?id=com.SWYP.kori)
[![App Store](https://img.shields.io/badge/App_Store-Kori-blue?style=for-the-badge&logo=apple)](https://apps.apple.com/be/app/kori-korea-foreigners-meet/id6752611613)


## 📈 Service Performance (서비스 성과)
* **운영 기간:** 2025. 08 ~ 현재
* **사용자 지표:** 누적 다운로드 **5,000+**, 총 가입 유저 **3,000+**, 평균 **DAU 100+**
* **글로벌 지표:** 전 세계 약 **100여 개국** 유저 유입 및 활동 중
* **팀 구성:** BE(3명), FE(3명), 디자이너(2명)


## 🏗 시스템 아키텍처 (System Architecture)
![Group 4.png](attachment:d353f834-e747-44e4-918e-e759e7f4dae4:3d644aeb-1446-4e63-984b-441d13e7d68b.png)



## ✨ 주요 기능 (Key Features)

### 💬 실시간 글로벌 채팅
- **WebSocket 기반 채팅:** 실시간 1:1 대화 및 커뮤니티 채팅 환경 구축
- **Firebase Cloud Messaging (FCM):** 채팅 알림 및 서비스 공지 푸시 발송

### 📝 커뮤니티 관리 및 자동화
- **K-Culture Feed:** 게시글 CRUD, 좋아요, 댓글 기능 구현
- **Spring Batch:** 대량 알림 전송, 랭킹 정산, 휴면 유저 전환 등 백그라운드 작업 자동화

### 🔐 인프라 및 보안
- **Database 관리:** Flyway를 이용한 운영 DB 스키마 형상 관리 및 데이터 정합성 유지
- **부하 테스트 (k6):** 실제 서비스 운영 전 트래픽 한계 측정 및 병목 구간 개선
- **실시간 모니터링:** Prometheus와 Grafana를 연동하여 서버 리소스 및 API 상태 실시간 관제

## 🛠 기술 스택 (Tech Stack)

### Language & Framework
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white">

### Database & Migration
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"> <img src="https://img.shields.io/badge/Flyway-CC0202?style=for-the-badge&logo=flyway&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white">

### Infrastructure & Monitoring
<img src="https://img.shields.io/badge/Naver%20Cloud-03C75A?style=for-the-badge&logo=naver&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white">
