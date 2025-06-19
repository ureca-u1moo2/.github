# 🍦 요플레(Yoplait)

> LG U+ 유레카 종합 프로젝트 1조  
> 2025.06.02 ~ 06.24

<div align="center">
  
<img src="https://github.com/user-attachments/assets/72ec3f69-a537-485c-b028-0e82770c92f8" height=500 width=500>

</div>

</br>

```
요플레(Yoplait)는 어떤 요금제를 사용할 지 고민하시는 여러분들께 요금제 추천을 도와주는 AI 챗봇입니다.
요플레와 달달한 대화를 하다보면 어느새 고민이 끝나 있을거에요.
```

- 🗣️ AI와 자연어 상담을 통한 맞춤형 요금제 추천  
- 🧠 대화 토픽 분류를 통한 질문 문맥 기반 대화 가능  
- 🗂️ Redis 와 MongoDB를 활용한 대화 내역 저장 및 분석  
- 🛡️ 백오피스의 금칙어 관리, 사용자 및 요금제 분석 AI를 통한 서비스 품질 향상  
- 📊 Elsaticsearch + Kibana 연동으로 사용자 행동 로그 시각화 및 분석

</br>

## 👥 팀원 소개

| 문태신(조장) | 장승범 | 신수현 | 이도연 |
|:--:|:--:|:--:|:--:|
| <img src="https://github.com/user-attachments/assets/cdad3cfb-bf0d-4388-a11e-44af0620193a" heigth=150 width=150> <br/> [@taeaeaexin](https://github.com/taeaeaexin) </br> Backoffice |  <img src="https://github.com/user-attachments/assets/d0157a3c-ef7d-4343-93ce-4b7cbcb9f439" heigth=150 width=150> <br/> [@JSeungBeom](https://github.com/JSeungBeom) <br/> Message Storage |  <img src="https://github.com/user-attachments/assets/f888c69e-4453-43fe-b1da-0e386d3f48da" heigth=150 width=150> <br/> [@suhyun9764](https://github.com/suhyun9764) <br/> Chat |  <img src="https://i.imgur.com/2MNf32S.png" heigth=150 width=150> <br/> [@doyeonLee-Luna](https://github.com/doyeonLee-Luna) <br/> Product |

|하령경|허승현|정성빈|
|:-:|:-:|:-:|
| <img src="https://github.com/user-attachments/assets/61d26e87-3fb4-4099-a698-03b5b3e314da" height=150 width=150> <br/> [@rxgx424](https://github.com/rxgx424) <br/> Auth & Session | <img src="https://github.com/user-attachments/assets/0ae674b1-7fe3-463b-81b5-04336f694968" height=150 width=150> <br/> [@HSH-11](https://github.com/HSH-11) <br/> Logging & Analytics | <img src="https://github.com/user-attachments/assets/8cd0c571-acbe-4f7b-b36c-0f78f1d0fbd2" height=150 width=150> <br/> [@tjdqls3607](https://github.com/tjdqls3607) <br/> NLP |


</br>


## 🚀 주요 기능

<table>
<tr>
<td valign="top">

### Main

| 기능 | 설명 |
| - | - |
| 회원가입/로그인 | - JWT 인증 방식 <br> - RTR 방식 |
| 이메일/비밀번호 찾기 | - 사용자 개인정보를 이용하여 이메일 찾기 <br> - 이메일로 비밀번호 재설정 링크 전송 |
| 보안 | - Spring Security 사용으로 접근 제한 처리 |
| 마이페이지 | - 가입한 요금제 조회 <br> - 월별 사용량 조회 <br> - 회원 정보 조회 |
| 요금제 검색/비교 | - 요금제 목록(인기순/데이터/가격순) 조회 가능 <br> - 요금제 상세 정보 페이지 <br> - 요금제 비교 페이지 |
| AI | - 챗봇 사용자 맞춤 상담 진행 <br> - 요금제 상세페이지 내 리뷰 요약 AI |

</td>
<td valign="top">

### Admin

| 기능 | 설명 |
| - | - |
| 관리자 회원가입/로그인 | - JWT 인증 방식 <br> - RTR 방식 |
| 대시보드 | - 챗봇 로그 기반 실시간 시각화 분석 <br> - 의도·응답시간 등 주요 지표 모니터링 |
| 사용자 분석 | - 사용자의 회선을 기반으로 <br> - 사용자 분석 |
| 요금제 분석 | - 모든 요금제 리스트 출력, 검색 및 정렬 필터 <br> - 요금제 가입 현황 AI 분석을 통해 요금제 개선 사항 참고 가능 |
| 금칙어 관리 | - 금칙어 리스트 |

</td>
</tr>
</table>



https://github.com/suhyun9764/planit/blob/dev/README.md
이거 참고해서 씁시다

## 🛠️ 기술 스택
<div align="center">

| 분야 | 스택 |
| - | - |
| Backend | [![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1750320970954?alt=media&token=930c4d9b-06ba-43f8-a395-c956d01ebb9b)](https://github.com/msdio/stackticon) |
| Frontend | [![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1750321043857?alt=media&token=afc93f42-9d5e-4e6d-bf1a-a67ffd8e5cbd)](https://github.com/msdio/stackticon) |
| AI/ML | [![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1750321207033?alt=media&token=83196575-12ff-49fc-ab10-e98bb19c3bc9)](https://github.com/msdio/stackticon) |
| DevOps & Monitoring | [![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1750321248550?alt=media&token=b447ee61-68af-4528-9439-aeeeff93ccfb)](https://github.com/msdio/stackticon) |

</div>


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

---

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


---

### 🎯 6월 4주차

<div align="center">


</div>

#### ✅ 금주 수행 내용
- [x] 사용자 테스트 및 피드백 수집
- [x] 버그 수정및 보완점 작성
- [x] 챗봇 고도화 및 코드 가독성 리팩토링
- [x] 시연영상 및 발표자료 문서작업
- [x] 더미데이터 제작 및 데이터 리팩토링


#### 🎯 최종 목표
- [ ] 프로젝트 완료 및 배포


---
