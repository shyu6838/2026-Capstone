# FindU

FindU는 교내 분실물과 습득물을 이미지 유사도 기반으로 매칭해주는 서비스입니다.

## 주요 기능

- 분실물 등록
- 습득물 등록
- CLIP + FAISS 기반 이미지 유사도 검색
- 위치, 시간, 텍스트 기반 추천 점수 계산
- 사용자 신뢰도 EXP 시스템
- 허위 등록 및 신고 패널티 시스템

## 기술 스택

### Frontend
- React
- TypeScript
- Axios

### Backend
- Spring Boot
- Spring Security
- JPA
- PostgreSQL
- AWS S3

### AI Server
- Python
- FastAPI
- CLIP
- FAISS

## 서버 구조

React → Spring Boot → PostgreSQL / S3  
Spring Boot → Python AI Server → CLIP + FAISS
