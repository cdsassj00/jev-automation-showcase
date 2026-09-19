# TypeSafe Jev 업무자동화 스위트 (System-1 AI Showcase)

> **"LLM이 자연어로 장황하게 설명하지 않고, 코드가 즉시 소비할 수 있는 확률(Noul)·점수(Score)·선택(Choice)을 반환합니다."**

TypeSafe의 플래그십 모델인 **Jev**는 긴 텍스트 생성 대신 **정형화된 판단(Structured Decision)**을 밀리초(ms) 단위로 병렬 수행하는 최초의 **System One AI 모델**입니다.

이 프로젝트는 Jev의 정량적 확률 판단값을 순수 JavaScript 로직(`if/else`, 가중치 연산)과 결합하여 **최종 업무 액션을 100% 자동으로 완결하는 4가지 실무 파이프라인**을 보여주는 정적 웹 애플리케이션입니다.

---

## 🚀 4대 실무 자동화 파이프라인

1. **CS 인박스 긴급 라우터 & 비상 알림**
   * **Jev Primitives**: 부서 분류(`Choice`), 긴급도(`Score`), 이탈/신고 가능성(`Noul`)
   * **완성된 액션**: 위험 확률 80% 이상 감지 시 즉시 슬랙 비상 채널 알림 및 긴급 대응 티켓 발행, 일반 건은 답변 초안 생성.

2. **채용 서류 스크리닝 & 면접 제안서 엔진**
   * **Jev Primitives**: 기술 적합도(`Score`), 리더십/협업(`Score`), 필수 경력 요건 충족(`Noul`)
   * **완성된 액션**: 자격 요건과 점수를 코드로 가중합산(100점 만점)하여 기준 충족 시 1차 기술 인터뷰 일정 예약 메일 발송 폼 완성.

3. **법인카드 규정 위반 심사 & ERP 전표 처리**
   * **Jev Primitives**: 사규 위반 확률(`Noul`), 업무 연관성(`Score`), 지출 분류(`Choice`)
   * **완성된 액션**: 위반 확률 80% 이상 시 전표 자동 반려 및 소명서 요구서 발행, 정상 건은 ERP 즉시 자동 승인.

4. **스마트 메일 트리아지 & To-Do 자동 등록**
   * **Jev Primitives**: 액션 필요성(`Noul`), 마감일 여부(`Noul`), 우선순위(`Choice`)
   * **완성된 액션**: 일정과 데드라인이 포함된 업무 요청은 Google Calendar & Notion 할 일로 즉시 등록.

---

## 🛠️ 기술 스택
* **Frontend**: HTML5, Vanilla JavaScript (ES6+), Tailwind CSS, FontAwesome
* **Architecture**: Serverless / Static Web App (GitHub Pages 배포 지원)
* **AI Model**: TypeSafe Jev (System-1 Architecture)

---

## 🌐 실행 방법
브라우저에서 `index.html` 파일을 직접 열거나, GitHub Pages를 통해 접속할 수 있습니다.
별도의 API 키 입력 없이도 데모 시뮬레이션 모드로 모든 파이프라인을 체험하실 수 있습니다.

