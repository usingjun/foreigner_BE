🇰🇷 Kori: Global K-Pop Community & Chat
Kori는 전 세계 팬들이 K-Pop, K-Drama를 매개로 소통하고 언어를 배우는 글로벌 커뮤니티 서비스입니다. 이 리포지토리는 Kori의 실시간 채팅, 콘텐츠 관리 및 AI 번역을 지원하는 백엔드 서버를 담고 있습니다.
[![Google Play](https://img.shields.io/badge/Google_Play-Kori-green?logo=googleplay)](https://play.google.com/store/apps/details?id=com.SWYP.kori)
[![App Store](https://img.shields.io/badge/App_Store-Kori-blue?logo=apple)](https://apps.apple.com/be/app/kori-korea-foreigners-meet/id6752611613)

📋 목차
핵심 기능

기술 스택

시스템 아키텍처

API 명세

프로젝트 설정

✨ 핵심 기능 (Key Features)
Kori의 주요 비즈니스 로직을 처리하는 백엔드 기능입니다.

글로벌 채팅 시스템: WebSocket/Socket.io를 활용한 실시간 팬 커뮤니티 채팅 및 1:1 대화 지원

AI 번역 통합: 글로벌 유저 간 원활한 소통을 위한 채팅 실시간 번역 API 연동

커뮤니티 및 포스트: K-Pop/K-Drama 관련 게시글 생성, 좋아요, 댓글 기능 및 페이징 처리

사용자 인증 및 프로필: JWT 기반 보안 인증 및 글로벌 유저 성향에 맞춘 프로필 관리

푸시 알림: 관심 있는 아이돌의 새 소식이나 채팅 알람 발송

🛠 기술 스택 (Tech Stack)


Language & Framework: Node.js (NestJS) / Java (Spring Boot)

Database: PostgreSQL / MongoDB (채팅 로그) / Redis (캐싱)

Infra: AWS EC2, S3, RDS, Docker

Tools: Swagger (API), GitHub Actions (CI/CD)

🏗 시스템 아키텍처 (System Architecture)


📖 API 명세 (API Documentation)
