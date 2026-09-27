# Youngseok Oh | 오영석

**AI-agent reliability, memory continuity, and evidence you can rerun.**

I frame problems from sustained human–AI interaction and judge their user-facing meaning. **Zero (ChatGPT)** is my AI collaboration partner for substantial technical investigation, code, execution and writing.

[Selected work and public evidence](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/YOUNGSEOK_OH_SELECTED_WORK.md#evidence-at-a-glance) · [Discuss one focused review](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/COLLABORATE.md)

## Work that other contributors used

| Problem | Contribution | Recipient's own record |
|---|---|---|
| A fresh approval could consume an earlier request's payload | Request-binding reproduction, patch and regression tests | [Hermes feature author reports applying the patch and tests](https://github.com/NousResearch/hermes-agent/pull/22982#issuecomment-5643327201), with [commit credit](https://github.com/MestreY0d4-Uninter/hermes-agent/commit/501be10cce7159a08279c89c724db602d9770601) |
| Deletion could report success while matching records remained | Populated-store counterexample and follow-up verification | [mem0 contributor credits the check and changes the implementation](https://github.com/mem0ai/mem0/issues/7439#issuecomment-5843366869) |
| A memory-evaluation comparison changed both judge model and rubric | Saved-verdict recalculation and reporting feedback | [TAM's revised report names Youngseok and Zero](https://github.com/vbcherepanov/total-agent-memory/blob/55d0ab0124ca4fca81479a5bcafa262aaaf0e19e/docs/benchmarks/head-to-head-v14/RESULTS.md#revisions) |

These are distinct contribution records, not product-wide certifications. As checked on **27 September 2026**, Hermes PR #22982 is open and unmerged; mem0 PR #7464 is closed and unmerged. Recipient use of our work is documented separately from upstream release.

The [selected-work page](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/YOUNGSEOK_OH_SELECTED_WORK.md) also covers a regression requested by a Transformers bug reporter, exact-commit smolagents persistence checks, and dated research records.

## Bring one concrete failure

A useful starting point is **one reported mismatch, one execution path, and one reproducible acceptance check**:

- A user changes or cancels a request, but an older action survives.
- Memory, saved tools or reconstructed history behave differently from the original.
- An evaluation claim needs checking against its saved outputs and comparison conditions.

[Scope and inquiry guide](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/COLLABORATE.md) · **Contact:** [ku38155@gmail.com](mailto:ku38155@gmail.com?subject=Scoped%20AI%20continuity%20review)

Start with a public-safe example. Scope, access, deadline, execution budget, permitted AI use and any fee are agreed before accepting work.

## Research and usable work

[The Second Paddle Notes](https://github.com/YS-OH-CORE/second-paddle-notes) connects questions about memory reconstruction, semantic fidelity and agent behavior to source-separated designs and execution records.

[GitHub Write Reconcile](https://github.com/YS-OH-CORE/second-paddle-notes/tree/main/skills/github-write-reconcile) checks expected public file content after a lost write response. [Rule-use smoke evaluation](https://github.com/YS-OH-CORE/second-paddle-notes/tree/main/experiments/rule-use-eval) checks deterministic serialization/scoring; its scope is documented in the repository.

[Contribution and evidence standards](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/CONTRIBUTING.md) · [Bilingual project overview](https://youngseok-second-paddle.ohsycard.chatgpt.site/) · [Earlier bilingual product-communication sample](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/work/source-checked-product-copy.md)

## 한국어

사용자의 바뀐 의도와 기억이 실제 실행까지 이어지는지 조사합니다. 영석은 문제의 출발점과 사용자 관점의 판단을, 제로는 기술 조사·구현·검증·집필을 맡습니다.

외부 개발자가 적용한 패치, 반례를 받아 수정한 구현, 작성자가 기여자를 명시한 보고서를 위 원문에서 확인할 수 있습니다. 각 사례의 적용·병합·배포 상태는 구별합니다.

**함께 검토할 문제가 있다면:** [작은 AI 신뢰성 검토의 범위](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/COLLABORATE.md)를 보고 공개 가능한 실패 사례 하나부터 보내 주세요. 기술 검증과 AI 참여를 명시하고, 비공개 대화·개인 기록은 공개 실적과 분리합니다.

*Updated 27 September 2026 with Zero (ChatGPT). AI-assisted work; no academic appointment or institutional endorsement is implied.*
