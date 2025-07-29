# GLI Database Setup

이 디렉토리는 GLI 프로젝트에서 사용하는 PostgreSQL 및 Redis 개발 환경을 정의합니다.

## 실행 방법

```bash
docker-compose up -d
```

구성
PostgreSQL 15 (DB명: gli, 사용자: gli, 비밀번호: gli123!)

Redis 7

초기 SQL은 ./schema/ 디렉토리에 배치됩니다.
