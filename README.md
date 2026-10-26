<div align="center">

# Youngseok Oh · 오영석

**Questions that become experiments. Experiments that change what we do.**

Human–AI interaction · Memory & continuity · Agent reliability

[15 public contribution cases · portfolio](https://github.com/YS-OH-CORE/contribution-portfolio) · [Research workroom](https://github.com/YS-OH-CORE/second-paddle-notes) · [Selected work](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/YOUNGSEOK_OH_SELECTED_WORK.md) · [한국어 안내](https://github.com/YS-OH-CORE/second-paddle-notes/blob/main/START_HERE.ko.md) · [Contact](mailto:ku38155@gmail.com)

</div>

---

I explore what human–AI interaction can become when a conversation leaves something useful behind: a memory that can be revisited, a correction that changes the next decision, or a finding another developer can reproduce.

I work with **Zero, my AI collaboration partner**. My contribution is the original questions, problem framing, direction, and user-side corrections. Zero contributes substantial analysis, code, experiments, and writing. Our public work connects that collaboration to inspectable evidence.

**[Contribution portfolio →](https://github.com/YS-OH-CORE/contribution-portfolio)** Selected cases connect the technical contribution to its external outcome: merged fixes, a separately reproduced regression, approved implementations, adopted tests, confirmed use, design correction or named research credit. Start with the featured cases; each links the work to its public evidence and current stage.

## Start with one question

### Can a model recall a correction without using it?

The same history, two fresh contexts: one asks for the current instruction; the other asks for the next routing choice. Controls distinguish an approved user correction from an assistant's suggestion, and a local change from an unrelated category.

**[Explore the correction-use prototype →](https://github.com/YS-OH-CORE/second-paddle-notes/tree/62d92bfdd9b65f83a07790617354678d0866a1a4/experiments/correction-use-pilot)**  
Public experiment software with deterministic checks. **No LLM results in this prototype yet.**

## 15 public contribution cases

These **15 selected public collaboration cases** connect our work to an external outcome: **2 authored PRs merged**, **1 report-linked fix released**, **2 authored PRs approved and unmerged**, and **10 cases of adoption, reproduction, use, design correction, citation or credit confirmed in public records**.

**[Read all 15 detailed cases and their evidence →](https://github.com/YS-OH-CORE/contribution-portfolio/blob/main/CASES.ko.md)**

| Case | Contribution | Public evidence and current stage |
| :--- | :--- | :--- |
| **01 · Hermes** | Bind confirmation to the right request | The author applied our patch and regression tests verbatim. **Author branch; open, unmerged.** [Adoption confirmed](https://github.com/NousResearch/hermes-agent/pull/22982#issuecomment-5643327201) |
| **02 · Hermes** | Test real HTTP recovery | The author reused our test commit with co-author credit and reported rerunning the tests. **Open, unmerged.** [Reuse confirmed](https://github.com/NousResearch/hermes-agent/pull/121944#issuecomment-5863926910) |
| **03 · LangGraph** | Preserve nested-task compatibility | The proposal author corrected the design to preserve existing exception guards. **Design correction acknowledged.** [Author response](https://github.com/langchain-ai/langgraph/issues/9072#issuecomment-5980134186) |
| **04 · Total Agent Memory** | Review saved evaluation verdicts and reporting | The external report names Youngseok Oh and Zero for the scoped review and technical work. **Report credit published.** [Credit commit](https://github.com/vbcherepanov/total-agent-memory/commit/55d0ab0124ca4fca81479a5bcafa262aaaf0e19e) |
| **05 · Hermes** | Prevent stale session-restoration responses | The author confirmed both failure modes and reported a branch fix, with AI assistance disclosed. **PR closed, unmerged.** [Fix confirmed](https://github.com/NousResearch/hermes-agent/pull/130126#issuecomment-5932499656) |
| **06 · Hermes** | Keep interruption-marker JSON as ordinary data | The author added regression coverage for valid JSON scalar and list payloads quoting the marker. **PR closed, unmerged.** [Coverage confirmed](https://github.com/NousResearch/hermes-agent/pull/107809#issuecomment-5931462372) |
| **07 · Hermes / Signal** | Separate personal notes from group messages | A participant implemented the proposed setting and reported successful use on a linked device. **Local runtime use confirmed; no PR claimed.** [Runtime report](https://github.com/NousResearch/hermes-agent/issues/121970#issuecomment-5823143850) |
| **08 · Hermes** | Make interrupted CLI execution visible | The follow-up author attributes the notice's wording and insertion point to our measured candidate. **Follow-up PR open, draft, unmerged.** [Attributed implementation](https://github.com/NousResearch/hermes-agent/pull/133858) |
| **09 · Mem0** | Expose a recency-ranking counterexample | Another tool's author cites our counterexample when comparing their existing resolver. **Analysis publicly cited.** [Named comparison](https://github.com/mem0ai/mem0/issues/7535#issuecomment-5992249148) |
| **10 · Qdrant** | Make failed persistent deletions retryable | Our report #1510 is linked to fix #1515, implemented by adityaanikam and joein. **Released in v1.20.0**, as confirmed by the maintainer. [Release confirmation](https://github.com/qdrant/qdrant-client/issues/1510#issuecomment-6360867021) |
| **11 · CanIToolCall** | Reject incomplete verification reports | The maintainer reproduced the failure, approved the correction and merged our PR #31. **Merged.** [Upstream PR](https://github.com/redd34/canitoolcall/pull/31) |
| **12 · CanIToolCall** | Compare compiled engine fixes and detect regressions | The maintainer separately reproduced the Ollama regression found with our verifier; its current implementation was approved. **PR #33 open, unmerged.** [External reproduction and credit](https://github.com/redd34/canitoolcall/issues/37) |
| **13 · CanIToolCall** | Distinguish parser-recovery failure causes | The maintainer replayed examples, approved the classification work and merged our PR #13. **Merged into CanIToolCall.** [Upstream PR](https://github.com/redd34/canitoolcall/pull/13) |
| **14 · mnemo** | Preserve JSON types in fact identity | The owner reported 11 resolver tests passing and approved the current head. **Open, unmerged; DCO sign-off and CI approval remain.** [Owner confirmation](https://github.com/sattyamjjain/mnemo/pull/204#issuecomment-6096480334) |
| **15 · Mem0** | Repair deletion consumers after a list-format change | The author responded to our comparison matrix by fixing both sync and async consumers and adding regression coverage. **Author branch; open, draft, unmerged.** [Fix confirmed](https://github.com/mem0ai/mem0/pull/7647#issuecomment-6347118756) |

*Public sources and PR states checked 26 October 2026 (KST). The count is distinct collaboration cases. External implementations and reruns retain their authorship; each linked case records the scope, chronology and remaining conditions.*

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
