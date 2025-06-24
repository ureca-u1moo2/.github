# 🍦 요플레(Yoplait)

> LG U+ 유레카 종합 프로젝트 1조  
> 2025.06.02 ~ 06.24

<div align="center">
  
<img src="https://github.com/user-attachments/assets/72ec3f69-a537-485c-b028-0e82770c92f8" height=500 width=500>

</div>

<br/>

```
요플레(Yoplait)는 어떤 요금제를 사용할 지 고민하시는 여러분들께 요금제 추천을 도와주는 AI 챗봇입니다.
요플레와 달달한 대화를 하다보면 어느새 고민이 끝나 있을거에요.
```

- 🗣️ AI와 자연어 상담을 통한 맞춤형 요금제 추천  
- 🧠 대화 토픽 분류를 통한 질문 문맥 기반 대화 가능  
- 🗂️ Redis 와 MongoDB를 활용한 대화 내역 저장 및 분석  
- 🛡️ 백오피스의 금칙어 관리, 사용자 및 요금제 분석 AI를 통한 서비스 품질 향상  
- 📊 Elsaticsearch + Kibana 연동으로 사용자 행동 로그 시각화 및 분석

<br/>

## 👥 팀원 소개

| 문태신(조장) | 장승범 | 신수현 | 이도연 |
|:--:|:--:|:--:|:--:|
| <img src="https://github.com/user-attachments/assets/cdad3cfb-bf0d-4388-a11e-44af0620193a" heigth=150 width=150> <br/> [@taeaeaexin](https://github.com/taeaeaexin) </br> Backoffice |  <img src="https://github.com/user-attachments/assets/d0157a3c-ef7d-4343-93ce-4b7cbcb9f439" heigth=150 width=150> <br/> [@JSeungBeom](https://github.com/JSeungBeom) <br/> Message Storage |  <img src="https://github.com/user-attachments/assets/f888c69e-4453-43fe-b1da-0e386d3f48da" heigth=150 width=150> <br/> [@suhyun9764](https://github.com/suhyun9764) <br/> Chat |  <img src="https://i.imgur.com/2MNf32S.png" heigth=150 width=150> <br/> [@doyeonLee-Luna](https://github.com/doyeonLee-Luna) <br/> Product |

|하령경|허승현|정성빈|
|:-:|:-:|:-:|
| <img src="https://github.com/user-attachments/assets/61d26e87-3fb4-4099-a698-03b5b3e314da" height=150 width=150> <br/> [@rxgx424](https://github.com/rxgx424) <br/> Auth & Session | <img src="https://github.com/user-attachments/assets/0ae674b1-7fe3-463b-81b5-04336f694968" height=150 width=150> <br/> [@HSH-11](https://github.com/HSH-11) <br/> Logging & Analytics | <img src="https://github.com/user-attachments/assets/8cd0c571-acbe-4f7b-b36c-0f78f1d0fbd2" height=150 width=150> <br/> [@tjdqls3607](https://github.com/tjdqls3607) <br/> NLP |

<br/>

## 💡 프로젝트 소개

### 🎯 프로젝트 목적
> 챗봇 기반 요금제·기종 추천 서비스 및 관리자용 통합 관리 시스템 구축을 통해 사용자에게 최적화된 통신 서비스를 제공

- 🗣️ **자연어 상담**을 통한 맞춤형 요금제 추천
- 🛡️ **금칙어 관리, 사용자 분석** 및 관리자 백오피스를 통한 서비스 품질 향상
- 🧠 **대화 토픽 분류**를 통한 질문 문맥 기반 대화 가능
- 🗂️ **Redis 와 MongoDB**를 활용한 대화 내역 저장 및 분석
- 📊 **Elsaticsearch + Kibana** 연동으로 사용자 행동 로그 시각화 및 분석

<br/>

### ✨ 핵심 차별점

<div align="center">
  
| 🤖 AI 기반 분석 | 🎯 개인화 추천 | 💬 멀티턴 대화 |
|:---:|:---:|:---:|
| Gemini AI | 사용 성향 맞춤 분석 | 지능형 대화 시스템 |
</div>

<br/>

## 🚀 주요 기능
<div align="center">
<table>
<tr>
<td style="width: 49%; vertical-align: top; border-right: 1px solid #ccc; padding-right: 10px;">

<h3>Main</h3>

<table>
<tr><th>기능</th><th>설명</th></tr>
<tr><td>회원가입/로그인</td><td>JWT 인증 방식<br>RTR 방식</td></tr>
<tr><td>이메일/비밀번호 찾기</td><td>이메일 찾기<br>비밀번호 재설정 링크 전송</td></tr>
<tr><td>보안</td><td>Spring Security 기반 접근 제한</td></tr>
<tr><td>마이페이지</td><td>가입 요금제, 사용량, 정보 조회</td></tr>
<tr><td>요금제 검색/비교</td><td>요금제 목록/상세/비교 페이지</td></tr>
<tr><td>AI</td><td>챗봇 상담, 리뷰 요약</td></tr>
</table>

</td>

<td style="width: 49%; vertical-align: top; padding-left: 10px;">

<h3>Admin</h3>

<table>
<tr><th>기능</th><th>설명</th></tr>
<tr><td>관리자 로그인</td><td>JWT 인증 방식<br>RTR 방식</td></tr>
<tr><td>대시보드</td><td>챗봇 로그 시각화<br>의도/응답시간 모니터링</td></tr>
<tr><td>사용자 분석</td><td>회선 기반 사용자 분석</td></tr>
<tr><td>요금제 분석</td><td>요금제 리스트·검색·정렬<br>AI 분석 기반 개선안 도출</td></tr>
<tr><td>금칙어 관리</td><td>금칙어 리스트</td></tr>
</table>

</td>
</tr>
</table>
</div>

<br/>

## 🛠 기술 스택

<div align="center">

### Backend
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### AI/ML
![Gemini](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)

### DevOps & Monitoring
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)

</div>

<br/>

## 🔗 프로젝트 자료

<div align="center">

| 📋 문서 | 🔗 링크 | 📝 설명 |
|:---:|:---:|:---:|
| 📄 기획안 | [Google Docs](https://docs.google.com/document/d/1RFvzAa7Amh1WPt2UKVyiIdVeLcTwyKSFmenKTzG4pDA/edit?tab=t.0) | 프로젝트 전체 기획서 |
| 📊 WBS | [Google Sheets](https://docs.google.com/spreadsheets/d/1H4jPiWKxPKsJQByPJhL61SquUI-iqkK9vX4k1c8HgyU/edit?gid=881356559#gid=881356559) | 작업 분해 구조 |
| 🖌 와이어프레임 | [Excalidraw](https://excalidraw.com/#room=c9f1f3cab06fe706f5b9,rnOkx3tL04rYI7KXJayPWg) | UI/UX 설계도 |
| 👥 사용자 UML | [Lucid Chart](https://lucid.app/lucidchart/eeda806c-2c79-48b1-99de-cbfe48c6babe/edit?invitationId=inv_85460dac-0f3b-408c-aed5-295030fac104&referringApp=slack&page=0_0#) | 사용자 시스템 설계 |
| 🛠 어드민 UML | [Lucid Chart](https://lucid.app/lucidchart/b060893d-c04f-456d-8c7b-ffebaf0d2942/edit?invitationId=inv_d9711542-1776-4475-8aee-e2b350d0b56e&referringApp=slack&page=0_0#) | 관리자 시스템 설계 |
| 📋 멘토링 문서 | [Notion](https://www.notion.so/20f8f7bcc50a805f9c63c9e545837867) | 멘토링 기록 정리 |
| 📝 수행일지 | [Google Docs](https://docs.google.com/document/d/18qC8GnYpRZdRfVA_0l-X0g1_VJ1Wr7gMZ659A6PfJX4/edit?tab=t.0) | 6월 2주차 프로젝트 수행일지 |
| 🖥️ ERD | [ERD Cloud](https://www.erdcloud.com/d/f25pp7HpDdBNEoeMK) | ERD 구성 |

</div>

<br/>

## ❓ 핵심 기술적 도전과제

<details>
<summary><b>🧠 MongoDB 기반 유저 대화 분석</b></summary>

- **현재 상황**: MongoDB 기반 유저 대화 기록 + Gemini 요약 분석 구현
- **고민사항**: 분석 결과의 실용적 활용 방안 및 확장 방향성
- **목표**: 사용자 성향 분석 정확도 향상

</details>

<details>
<summary><b>🎯 멀티턴 토픽 분류 최적화</b></summary>

- **현재 상황**: 최근 대화 포함 방식으로 구현
- **고민사항**: 멀티턴 분류 정확도 개선 필요
- **목표**: 대화 맥락을 고려한 정확한 토픽 분류

</details>

<details>
<summary><b>💾 Redis 세션 관리 최적화</b></summary>

- **현재 상황**: 유저/봇 각 10개씩 총 20개 대화 유지
- **고민사항**: 적절한 세션 크기 및 관리 방식
- **목표**: 효율적인 대화 컨텍스트 관리

</details>

<details>
<summary><b>📊 Elasticsearch 로그 활용도 극대화</b></summary>

- **현재 상황**: 기본 모니터링 기능 구현
- **고민사항**: 실시간 자동 반영 시스템 구축 필요성
- **목표**: 로그 데이터 기반 서비스 자동 개선

</details>

<details>
<summary><b>🔍 챗봇 추천 시스템 고도화</b></summary>

- **현재 상황**: 임베딩 기반 전체 질문 검색 후 필터링
- **고민사항**: 더 정밀한 추천 로직 설계 필요
- **목표**: 사용자 의도에 맞는 정확한 추천

</details>

<br/>

## 📈 프로젝트 진행 기록

### 🔥 6월 2주차

<div align="center">


</div>

#### ✅ 금주 수행 내용
- [x] 요금제·유저 관리 및 멤버십 연동(관리자)
- [x] 요금제 목록 조회·상세·비교 구현 + 요금제 가입·해지 + 요금제 리뷰 CRUD(사용자)
- [x] WebFlux 기반 챗봇 API 연동 및 멀티턴 대응 토픽 분류·프롬프트 전략 구현
- [x] Redis·MongoDB 기반 대화 저장 및 Gemini API 활용 유저 요약 분석, 월별 데이터 사용량 조회 기능 구현
- [x] 금칙어 필터링 알고리즘 구현 및 금칙어 테이블 생성
- [x] JWT 기반 로그인·회원가입·아이디 및 비밀번호 찾기
- [x] FastAPI를 이용한 벡터 임베딩 기능 구현, Elasticsearch 대화 로그 저장 및 Kibana를 통한 분석

#### 🚧 차주 수행 계획
- [ ] 요금제·유저 AI 분석
- [ ] 상태 머신 적용, 성향 분석 로직 구현
- [ ] 요금제 목록·상세·비교·리뷰 프론트 구현
- [ ] AI 유저 요약 분석 기능 프롬프트 고도화, 프로젝트 배포 세팅
- [ ] 관리자 프로젝트에서 금칙어 관리 CRUD 구현
- [ ] OAuth 도입
- [ ] ResTemplate -> WebClient 비동기 처리

<br/>

### 🎯 6월 3주차

<div align="center">


</div>

#### ✅ 금주 수행 내용
- [x] 요금제·유저 AI 분석
- [x] 상태 머신 적용, 성향 분석 로직 구현
- [x] 요금제 목록·상세·비교·리뷰 프론트 구현
- [x] AI 유저 요약 분석 기능 프롬프트 고도화, 프로젝트 배포 세팅
- [x] 관리자 프로젝트에서 금칙어 관리 CRUD 구현
- [x] ResTemplate -> WebClient 비동기 처리
- [x] 토픽 분류 정확도 개선을 위한 프롬프트 리팩토링


#### 🚧 차주 수행 계획
- [ ] 사용자 테스트 및 피드백 수집
- [ ] 버그 수정및 보완점 작성
- [ ] 챗봇 고도화 및 코드 가독성 리팩토링
- [ ] 시연영상 및 발표자료 문서작업
- [ ] 더미데이터 제작 및 데이터 리팩토링

<br/>

### 🎯 6월 4주차

<div align="center">

</div>

#### ✅ 금주 수행 내용
- [x] 사용자 테스트 및 피드백 수집
- [x] 버그 수정및 보완점 작성
- [x] 챗봇 고도화 및 코드 가독성 리팩토링
- [x] 시연영상 및 발표자료 문서작업
- [x] 더미데이터 제작 및 데이터 리팩토링

<br/>

#### 🎯 최종 목표
- [ ] 프로젝트 완료 및 배포

<br/>

<div align="center">
  <h3>🚀 함께 만들어가는 혁신적인 통신 서비스</h3>
  <p><i>"AI와 함께하는 스마트한 통신 생활의 시작"</i></p>
  
  <p>
    <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge" alt="Made with Love"/>
    <img src="https://img.shields.io/badge/Team-7%20Members-blue?style=for-the-badge" alt="Team Size"/>
  </p>
</div>




<div align="center">

**🌟 Star를 눌러 프로젝트를 응원해주세요! 🌟**

</div>
