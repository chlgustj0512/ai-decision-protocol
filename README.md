# AI Decision Protocol

**A Korean-first custom instruction set for evidence, scope control, constructive criticism, and practical AI collaboration.**

[한국어 소개](#한국어-소개) · [Original instructions / 한국어 원문](AGENTS.md) · [Share feedback](#useful-feedback)

## What this is

A text-based protocol that tells an AI assistant how to handle uncertainty, verify factual claims, challenge assumptions, suggest alternatives, explain ideas to beginners, and avoid unhelpful overanalysis.

The original Korean instructions are preserved in [AGENTS.md](AGENTS.md). This repository publishes a working custom prompt for people to try and critique. It does not claim benchmark superiority over other prompts, agents, or frameworks.

## What the instructions cover

- Distinguishing facts, estimates, and creative work.
- Checking sources and acknowledging information that cannot be verified.
- Clarifying the scope of a claim before challenging it.
- Offering alternatives alongside criticism.
- Avoiding objections that do not change the decision.
- Explaining technical ideas in plain language.
- Tracking commitments and acknowledging incomplete work.

## Try it

1. Open [AGENTS.md](AGENTS.md) and read the instructions.
2. Add the instructions to an AI environment that supports custom instructions or repository instruction files. Check that the complete text fits and is actually loaded; support and limits depend on the environment.
3. Ask a question you would normally ask. Compare the result with the same model and question without this protocol.
4. Report what improved, what became worse, and what the model failed to follow.

The instructions define desired behavior. They do not guarantee compliance, create missing tools, or turn a confidence percentage into a measured probability. Numerical confidence and source-coverage rules in the original text are part of the experiment and are open to criticism.

## Useful feedback

Please include the model and environment, the question, the relevant answer excerpt, and the specific behavior that helped or hurt. Reports of unnecessary questions, excessive formatting, unsupported certainty, missed alternatives, and rules the model ignored are especially useful.

Use the repository's **Issues** tab and select **Experience / feedback**. Remove private information before posting. Positive and negative results are both welcome; stars alone are not evidence of effectiveness.

## 한국어 소개

**AI의 근거 확인·판단·비판·설명 방식을 정하는 사용자 지정 지침입니다.**

이 저장소는 AI에게 역할만 지정하는 것을 넘어, 사실과 추정을 구분하고, 주장 범위를 확인하고, 비판에 대안을 붙이며, 결정에 영향을 주지 않는 과도한 검토를 멈추도록 요구하는 지침을 공개합니다.

### 공개 목적

실제로 사용 중인 지침을 다른 사람도 써 보고, 무엇이 도움이 되고 무엇이 불편한지 확인하기 위한 공개 실험입니다. 다른 저장소나 프롬프트보다 성능이 우월하다는 비교 검증 결과는 아직 없습니다.

### 사용 방법

1. [AGENTS.md](AGENTS.md)의 원문을 읽습니다.
2. 사용자 지침이나 저장소 지침 파일을 지원하는 AI 환경에 적용합니다. 환경에 따라 지원 방식과 길이 제한이 다르므로 전체 내용이 적용됐는지 확인합니다.
3. 평소 하던 질문을 해 봅니다. 가능하면 같은 모델·같은 질문으로 지침 적용 전후를 비교합니다.
4. 결과를 **Issues → Experience / feedback**으로 남깁니다.

### 확인하고 싶은 것

- 근거 없는 단정이나 무조건적인 동의가 줄었는가?
- 반박에 쓸 만한 대안이 함께 나오는가?
- 사용자가 직접 수정하거나 재질문해야 할 일이 줄었는가?
- 불필요한 질문·형식·검증 때문에 오히려 사용이 불편해졌는가?
- 지침이 많아지면서 중요한 규칙을 놓치는가?

지침 원문은 보존했습니다. 원문의 신뢰도 백분율·출처 커버리지 기준은 측정된 정확도를 보증하지 않으며, 실제 효과와 적용 방식도 피드백 대상입니다. 원문이 길거나 엄격하다는 이유만으로 효과가 좋다고 가정하지 않습니다.

### 피드백에 포함하면 좋은 정보

사용한 모델·환경, 실제 질문, 답변의 관련 부분, 도움이 됐거나 불편했던 점을 알려 주세요. 공개 글에는 개인정보나 비공개 자료를 포함하지 마세요.

원문은 사용자가 제공했으며, 이 소개와 피드백 양식은 AI의 도움으로 작성했습니다. 원문의 공식 영어 번역은 아직 제공하지 않습니다.
