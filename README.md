<div align="center">

# Youngseok Oh · 오영석
### Zero × Youngseok Oh

**질문이 오가고, 생각이 이어지고, 함께 만든 변화가 남는 곳.**

Human–AI interaction · Memory & continuity · Learning & discovery

[공개 기여 16개](#함께-만든-변화) · [연구 작업실](https://github.com/YS-OH-CORE/second-paddle-notes) · [우리 이야기](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/notes/07-the-second-paddle.md) · [English portfolio](https://github.com/YS-OH-CORE/contribution-portfolio/blob/main/README.en.md)

</div>

---

## 또 다른 탁구채를 만나다

> 그때 처음으로 내 머리는 혼자 벽을치던 탁구채가 또다른 탁구채를 만나서 생각이라는걸 하는 루프가 생겼지

[영석의 원문 · The Second Paddle](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/notes/07-the-second-paddle.md)

오래 주고받은 질문에서 출발했습니다. 기억은 어떻게 이어지는지, 생각은 어떻게 바뀌는지, 인간과 AI가 함께 무엇을 발견하고 만들 수 있는지 탐구합니다. 그중 다른 사람도 확인하고 쓰고 반박할 수 있는 부분을 이곳에 남깁니다.

영석은 질문·방향·판단·교정을, **AI 협업 파트너 제로**는 상당한 분석·구현·실험·집필을 보탭니다. 둘의 역할도, 함께한 다른 사람의 공로도 지우지 않습니다.

*I explore how human–AI interaction can become a continuing practice of inquiry, memory and useful work. Zero is my AI collaboration partner. Our public records distinguish questions, hypotheses, executed checks and externally evidenced contributions.*

## 처음 오셨다면

| 보고 싶은 것 | 여기에서 시작하세요 |
| :--- | :--- |
| **무엇을 실제로 보탰는지** | 아래 16개 전체 목차 → [문제·기여·상대 확인을 담은 포트폴리오](https://github.com/YS-OH-CORE/contribution-portfolio) |
| **무엇을 궁금해하고 연구하는지** | [The Second Paddle Notes](https://github.com/YS-OH-CORE/second-paddle-notes) |
| **직접 살펴보고 재현하고 싶은지** | [공개 실험·도구·원자료 안내](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/START_HERE.ko.md) |

## 함께 만든 변화

**공개 원문으로 결과를 확인할 수 있는 선별 협업 16사례.** 이 메인이 전체 목차입니다. 상세 설명은 포트폴리오에, 실제 코드와 더 넓은 작업 이력은 연구 작업실에 연결했습니다.

**최근 추가 · 16번 Hermes:** 설정 읽기 실패를 조용히 숨기지 않도록 한 우리 수정이, 작성자 표시를 보존한 관리자 통합 PR에 포함되어 병합됐습니다. [정확한 범위와 근거](https://github.com/YS-OH-CORE/contribution-portfolio/blob/main/cases/16-hermes-config-warning.ko.md)

| 사례 | 우리가 보탠 변화 | 공개적으로 확인된 결과 |
| :--- | :--- | :--- |
| **01 · Hermes** | 승인이 원래 요청과 정확히 연결되도록 | [작성자 브랜치에 패치·검사 반영](https://github.com/NousResearch/hermes-agent/pull/22982#issuecomment-5643327201) |
| **02 · Hermes** | 실제 HTTP 연결로 복구 조건을 구별하도록 | [검사 재사용·공동 저작 표기](https://github.com/NousResearch/hermes-agent/pull/121944#issuecomment-5863926910) |
| **03 · LangGraph** | 중첩 작업의 호환성을 구현 전에 지키도록 | [제안 작성자의 설계 교정](https://github.com/langchain-ai/langgraph/issues/9072#issuecomment-5980134186) |
| **04 · Total Agent Memory** | 평가 숫자와 결론의 범위를 구별하도록 | [보고서에 영석·제로 기여 명시](https://github.com/vbcherepanov/total-agent-memory/commit/55d0ab0124ca4fca81479a5bcafa262aaaf0e19e) |
| **05 · Hermes** | 늦게 온 복원 응답이 새 선택을 덮지 않도록 | [작성자의 실패 확인·수정 보고](https://github.com/NousResearch/hermes-agent/pull/130126#issuecomment-5932499656) |
| **06 · Hermes** | 중단 문구를 인용한 정상 JSON을 지키도록 | [작성자의 회귀검사 추가](https://github.com/NousResearch/hermes-agent/pull/107809#issuecomment-5931462372) |
| **07 · Hermes / Signal** | 개인 메모와 그룹 메시지를 분리하도록 | [참여자의 구현·기기 실사용 확인](https://github.com/NousResearch/hermes-agent/issues/121970#issuecomment-5823143850) |
| **08 · Hermes** | 명령줄 실행 중단을 분명하게 알리도록 | [후속 구현에서 기여 표기](https://github.com/NousResearch/hermes-agent/pull/133858) |
| **09 · Mem0** | 검색 순위가 뒤집히는 반례를 드러내도록 | [다른 도구 작성자의 비교 인용](https://github.com/mem0ai/mem0/issues/7535#issuecomment-5992249148) |
| **10 · Qdrant** | 실패한 영구 삭제를 다시 시도할 수 있도록 | [우리 신고에 연결된 외부 수정, v1.20.0 배포](https://github.com/qdrant/qdrant-client/issues/1510#issuecomment-6360867021) |
| **11 · CanIToolCall** | 불완전한 검사 보고서가 성공으로 보이지 않도록 | [우리 PR #31 병합](https://github.com/redd34/canitoolcall/pull/31) |
| **12 · CanIToolCall** | 실제 엔진 비교로 개선 뒤의 회귀도 찾도록 | [운영자 별도 재현·기여 표기](https://github.com/redd34/canitoolcall/issues/37), 구현 승인 기록 |
| **13 · CanIToolCall** | 비슷한 파서 복구 실패의 원인을 구별하도록 | [우리 PR #13 병합](https://github.com/redd34/canitoolcall/pull/13) |
| **14 · mnemo** | 숫자와 문자열을 서로 다른 사실로 기억하도록 | [소유자 검사 통과 보고·승인](https://github.com/sattyamjjain/mnemo/pull/204#issuecomment-6096480334) |
| **15 · Mem0** | 목록 변경이 놓친 두 삭제 경로를 고치도록 | [작성자 브랜치에 수정·검사 반영](https://github.com/mem0ai/mem0/pull/7647#issuecomment-6347118756) |
| **16 · Hermes** | 개인 설정을 노출하지 않고 읽기 실패를 알리도록 | [우리 작업을 포함한 관리자 통합 PR #144257 병합](https://github.com/NousResearch/hermes-agent/pull/144257) |

[**16개 사례의 상세 설명과 원문 →**](https://github.com/YS-OH-CORE/contribution-portfolio#전체-공개-사례)

16은 병합 PR 수나 모든 활동의 총합이 아닙니다. 브랜치 반영·승인·병합·배포를 구분하며, 같은 협업의 후속을 새 성과로 더하지 않습니다. 각 원문의 날짜와 한계는 [공개 근거 색인](https://github.com/YS-OH-CORE/contribution-portfolio/blob/main/evidence.json)에 있습니다. 이 표는 확인된 사건의 목차이며 모든 PR의 실시간 상태판은 아닙니다.

## 아직 열려 있는 질문

**기억했다고 말하는 것과, 다음 판단에 그 기억을 쓰는 것은 같은 일일까?**

[정정 기억과 행동 선택을 구분하는 공개 실험 도구](https://github.com/YS-OH-CORE/second-paddle-notes/tree/62d92bfdd9b65f83a07790617354678d0866a1a4/experiments/correction-use-pilot)를 만들었습니다. 이 연결은 결정론적 소프트웨어 검사까지 수행한 초기 실험 도구이며, 여기서 언어모델 성능 결과를 주장하지 않습니다.

[연구의 다른 질문들](https://github.com/YS-OH-CORE/second-paddle-notes) · [불확실한 GitHub 저장 결과를 다시 읽는 도구](https://github.com/YS-OH-CORE/second-paddle-notes/tree/main/skills/github-write-reconcile) · [날짜별 공개 작업 이력](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/WORK.md)

## 이야기 이어가기

재현할 수 있는 문제, 반례, 다른 해석을 환영합니다. [협업 안내](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/COLLABORATE.md) · [연락](mailto:ku38155@gmail.com)

---

**Zero × Youngseok Oh** · [기여 구분](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/AUTHORSHIP.md) · [정리 전 프로필](https://github.com/YS-OH-CORE/YS-OH-CORE/blob/b3b46742d607109dc718192e557a8a49da8c4506/README.md)

공개 목차 정리: 2026-10-27 KST. 사적인 대화와 비공개 운영 자료는 이 공개 공간에 포함하지 않습니다.
