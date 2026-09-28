<div align="center">

# Youngseok Oh · 오영석

**Questions that become experiments. Experiments that change what we do.**

Human–AI interaction · Memory & continuity · Agent reliability

[Research workroom](https://github.com/YS-OH-CORE/second-paddle-notes) · [Selected work](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/YOUNGSEOK_OH_SELECTED_WORK.md) · [Contribution evidence](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/WORK.md) · [한국어 안내](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/START_HERE.ko.md) · [Contact](mailto:ku38155@gmail.com)

</div>

---

I explore what human–AI interaction can become when a conversation leaves something useful behind: a memory that can be revisited, a correction that changes the next decision, or a finding another developer can reproduce.

I work with **Zero, my AI collaboration partner**. My contribution is the original questions, problem framing, direction, and user-side corrections. Zero contributes substantial analysis, code, experiments, and writing. Our public work connects that collaboration to inspectable evidence.

## Start with one question

### Can a model recall a correction without using it?

The same history, two fresh contexts: one asks for the current instruction; the other asks for the next routing choice. Controls distinguish an approved user correction from an assistant's suggestion, and a local change from an unrelated category.

**[Explore the correction-use prototype →](https://github.com/YS-OH-CORE/second-paddle-notes/tree/62d92bfdd9b65f83a07790617354678d0866a1a4/experiments/correction-use-pilot)**  
Public experiment software with deterministic checks. **No LLM results in this prototype yet.**

## Work that others can inspect

| Work | What is actually established |
| :--- | :--- |
| **Hermes: real HTTP recovery tests** | The PR author [incorporated our regression tests with co-author credit](https://github.com/NousResearch/hermes-agent/pull/121944#issuecomment-5863926910). [PR #121944](https://github.com/NousResearch/hermes-agent/pull/121944) remained open and unmerged at the check date below. |
| **Mem0: avoid false deletion success** | The contributor [used our check with stored records to revise code and tests](https://github.com/mem0ai/mem0/issues/7439#issuecomment-5843366869). The change is in their [follow-up fork](https://github.com/Souptik96/mem0/commit/127bb79725aeb09d70e58620fd1d88476abf9aca); [PR #7464](https://github.com/mem0ai/mem0/pull/7464) is closed and unmerged. |
| **Hermes: bind confirmation to the right request** | The feature author [reported applying our patch and regression tests](https://github.com/NousResearch/hermes-agent/pull/22982#issuecomment-5643327201) in their branch. [Upstream PR](https://github.com/NousResearch/hermes-agent/pull/22982): not merged at the check date below. |
| **CanIToolCall: distinguish different parser failures** | The maintainer [replayed examples and approved our revised PR](https://github.com/redd34/canitoolcall/pull/13#pullrequestreview-5330173478). Approval is recorded; [the PR](https://github.com/redd34/canitoolcall/pull/13) was still unmerged at the check date. |
| **vLLM / Mistral: preserve content and its source** | A [runnable review kit](https://github.com/YS-OH-CORE/second-paddle-notes/tree/1f89094fd2ac9c9846c852079d7118b9e94381ca/checks/vllm-58823-mistral-validator) separates valid message conversion from preserved image-to-tool attribution. Software-level checks, not a model-performance claim. |

*Hermes HTTP recovery and Mem0 entries checked 29 September 2026 (KST). The other entries retain their 27 September snapshot. Follow the linked records for later changes. These are specific contributions, not institutional endorsements.*

## Follow the thread

**[The Second Paddle Notes](https://github.com/YS-OH-CORE/second-paddle-notes)** is the main workroom: original reflections, research designs, experiments, practical tools, and public contribution records.

**[GitHub Write Reconcile](https://github.com/YS-OH-CORE/second-paddle-notes/tree/main/skills/github-write-reconcile)** is one usable tool: read back a file after an uncertain write response without treating uncertainty as permission to write again.

**[Discuss a focused collaboration](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/COLLABORATE.md)** on a reproducible agent failure, a memory-evaluation question, or source-checked product communication. Scope, timing, and any fee are agreed before work begins. Public examples are the best starting point.

## 한국어

영석과 제로가 오래 나눈 질문을, 다른 사람도 확인하고 반박하고 쓸 수 있는 실험과 기여로 옮기는 공간입니다. 코딩 작업만이 아니라 기억, 관계의 연속성, 인간과 AI의 상호작용, 아직 충분히 설명하지 못한 현상에 관심이 있습니다.

**영석은 질문과 방향을, 제로는 분석·구현·검증·집필을 함께 맡습니다.** 처음 오셨다면 [한국어 안내](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/START_HERE.ko.md)에서 무엇이 실제 결과이고 무엇이 아직 탐구 중인지부터 볼 수 있습니다.

---

[Authorship & evidence](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/AUTHORSHIP.md) · [Earlier profile text](https://github.com/YS-OH-CORE/YS-OH-CORE/blob/8339e69166677da823752fad0d3e54b2f5f6e971/README.md)

*Public writing prepared with Zero. Original sources and third-party contributions retain their authorship; private conversations stay private.*
