# 🏕️ Camping Event Reservation System
개인 프로젝트 (Naver Cloud 기반 3-Tier 아키텍처)
> Date: 2025/08/4 ~ 2025/09/30

## Description 
캠핑장 이벤트 예약을 효율적으로 관리하기 위해 설계된 **3-Tier 기반 웹 시스템**

Naver Cloud Platform을 기반의 멀티존 이중화 구조 및 CI/CD 파이프라인 구축

## Architecture
<img width="1659" height="846" alt="Image" src="https://github.com/user-attachments/assets/d7db7815-521d-4b76-80e5-4af2c5dacf7d" />

**구성 요소**
- **Platform:** Naver Cloud
- **Web Tier:** Apache (정적 페이지 서비스)
- **WAS Tier:** Spring Boot (내장 tomcat) (로그인 및 예약 처리)
- **DB Tier:** MySQL (예약 및 사용자 데이터 관리)
- **Session:** CDB for Cache (로그인 세션 관리)
- **CI/CD:** Source Pipeline
