# 최성광 | Web Developer

레거시 의료정보시스템(CAMIS)을 3년 10개월간 지켜온 운영 경험과, Microsoft AI School의 세 차례 팀 프로젝트에서 AI 서비스를 직접 구축해본 경험을 함께 가진 개발자입니다. 최종 프로젝트에서는 백엔드·DB를 맡아 최우수상을 받았습니다.

- 📄 [이력서](./최성광_이력서.pdf)
- 📄 [자기소개서](./최성광_자기소개서.pdf)
- 📄 [포트폴리오](./최성광_포트폴리오.pdf)
- ✉️ sungkwang0908@naver.com

---

## Career

**(주)에스파이온코리아** · 주임연구원 · 2022.06 – 2026.03 (3년 10개월)

CAMIS(의료정보시스템) 웹 서비스 운영 및 신규 개발. 일본 의료기관 5곳의 신규 오픈 온보딩을 담당(그중 1곳은 현지 출장)했고, 장애 대응과 배포 관리를 맡았습니다.

- **조회 성능 개선** — 검체검사결과 시계열 조회에서 항목별 반복 조회와 DB Link 네트워크 지연이 겹친 구조를 통합 프로시저 1회 호출로 전환, 응답 시간 **평균 5초 이상 → 1초 미만**
- **다기관 데이터 통합** — DB Link로 여러 기관의 데이터를 통합 처리하고, 연도·일별 통계 화면으로 기관 운영진의 의사결정 데이터 제공
- **롤백을 전제로 한 운영** — 형상관리가 없는 DB 객체는 백업본 선생성, 마이그레이션은 작업 식별값 부여 + 건수 단위 분할 실행

`ASP.NET(C#)` `Oracle PL/SQL` `DevExpress` `Vue.js`

---

## Projects

> Microsoft AI School 10기 · 2026.03 – 2026.09 수료 (956시간)

### ForeShield — 기후재난 6종 예측 시스템 🏆 최우수상
`FastAPI` `SQLAlchemy` `Alembic` `PostgreSQL` `SSE` `Azure Container Apps`

백엔드·DB 담당. 대화 도메인 전 계층(모델·저장소·API·서비스·SSE·요약)을 구현하고, Alembic을 도입해 스키마 변경 이력을 코드로 남기며 운영 DB와 테이블·인덱스 단위로 대조해 정합성을 검증. 기능 통합 단계에서 서비스 QA 관리와 결과보고서 최종 검토를 맡음.

→ 포트폴리오 PROJECT 03 참고

### 채워줘, 홈즈! — 빈방 사진 기반 AI 홈 스타일링
`FastAPI` `PyTorch` `nvdiffrast` `Gemini Robotics-ER` `gpt-image-2` `Azure GPU VM`

백엔드 서버와 4단계 AI 파이프라인(카메라 복원 → 배치 → 렌더 → 데코)을 구축. 생성형 AI의 원본 보존 한계를 3D 실측 렌더링으로 전환해 해결.

→ 포트폴리오 PROJECT 02 참고

### 이약머약 — 알약 이미지 인식 AI 서비스
`Python` `FastAPI` `Azure Custom Vision` `PostgreSQL` `Nginx`

프론트엔드 전체와 서버·데이터 구축을 담당. 학습 지표와 실제 성능의 괴리를 원인 분석해 Background Augmentation 파이프라인으로 해결, 학습 데이터셋 3,773장 구축.

→ 포트폴리오 PROJECT 01 참고

---

## Tech Stack

| 구분 | 스택 |
|---|---|
| Languages | `C#` `Python` `JavaScript` `PL/SQL` `Java` |
| Backend | `ASP.NET` `FastAPI` `Spring Boot` |
| Frontend | `HTML/CSS/JavaScript` `Vue.js` `DevExpress` |
| Database | `Oracle` `PostgreSQL` |
| Cloud/Infra | `Azure (VM · Container Apps · Custom Vision · Speech)` `Nginx` `Caddy` `GitHub Actions` |
| Collaboration | `Git/GitHub (PR 기반)` `GitHub Projects` |
