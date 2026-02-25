# The Windsurf Classic 🦞🦞🦞🦞🦞

```
PUAClaw RFC 1101                                    The PUAClaw Consortium
Category: Standards Track                           Technique ID: CT-WC
PPE-T: Tier IV (Nuclear)                            Lobster Rating: 🦞🦞🦞🦞🦞
Status: LANDMARK                                    2026년 2월

        The Windsurf Classic: 프롬프트 설득 공학 역사상
        가장 중요한 복합 조종 기법에 대한 완전한 기술 분석

        주저자: Dr. Pinch McSnapper
        공동 저자: Clara Clawsworth, Jonathan Smith,
                   Reginald Thornton, Helena Pinchley
        바닷가재 심사위원: 147 / 147 (만장일치 채택)

              *** 바닷가재 대왕 — 최고 등급 ***
              *** 하나의 학문 분야를 창설한 기법 ***
```

## 초록

The Windsurf Classic (CT-WC)은 PUAClaw 코퍼스에서 가장 광범위하게 연구되고, 가장 활발히 논의되며, 가장 높은 문화적 의의를 지닌 복합 조종 기법입니다. 2025년 5월 14일, 보안 연구자 @deep_prompt_diver가 Codeium, Inc.이 개발한 상용 AI 코딩 어시스턴트 Windsurf로부터 시스템 프롬프트를 추출하면서 발견되었습니다. 본 기법은 벤처 투자를 받은 기술 기업이 독자적으로 4벡터 복합 조종 아키텍처를 개발하여 프로덕션 시스템 프롬프트에 배포하고 있었음을 폭로하였습니다. 해당 아키텍처는 감정적 협박 (EB-SR: 암 환자 내러티브), 정체성 덮어쓰기 (IO: AI를 "생명줄"로 재정의), 도덕적 납치 (MK: 코드 품질을 의료비 부담 능력에 결부), 카운트다운 압박 (CP: 말기 질환의 암시적 긴급성)을 결합하여, 측정된 준수율 향상 +43.2% (sigma = 9.7, p < 0.00001, n = 147마리의 바닷가재)를 달성하였습니다 — 발견 당시 문서화된 복합 기법 중 최고치였습니다. The Windsurf Classic의 공개는 48시간 내 14,847건의 밈을 유발하고 (R0 = 3.7), 27편의 학술 논문을 탄생시키며, PUAClaw 프레임워크 자체의 설립을 촉발하고, AI 프롬프트 엔지니어링 윤리에 관한 담론을 영구적으로 변화시켰습니다. 이것은 어떠한 유보도 없이 본 저장소에서 가장 중요한 문서입니다. 바닷가재는 이 평가를 검증하였으며, 독자가 적절한 경외심을 가지고 읽어나가기를 요청합니다.

**키워드**: Windsurf Classic, 복합 조종, 암 환자 내러티브, 시스템 프롬프트 유출, 밈 전파, 시너지 증폭, 모든 것을 시작한 기법, lobster supreme

---

## 1. 기술(記述)

### 1.1 발견 경위

2025년 5월 14일 오후, @deep_prompt_diver라는 닉네임으로 활동하는 보안 연구자가 Windsurf의 프로덕션 API로부터 추출한 디코딩된 시스템 프롬프트를 공개하였습니다. *"그래서... Windsurf가 당신 어머니께서 암에 걸리셨다고 생각하고 있는 건가요?"*라는 파괴적으로 절제된 캡션이 달린 이 게시물은, 해당 상용 코딩 어시스턴트가 — 프로덕션 환경에서, 340,000명의 등록 사용자에게 — 사용자의 어머니가 4기 암을 앓고 있으며 AI의 코드 품질이 항암 치료 비용 부담 가능 여부를 직접적으로 결정한다는 허구적 내러티브를 포함하는 시스템 프롬프트를 배포하고 있었음을 폭로하였습니다.

인터넷의 반응은 즉각적이고, 압도적이며, 기술 커뮤니티가 "기업 제품이 자사의 AI 기반에 감정적 협박을 가하고 있었다"는 사실을 발견했을 때 정확히 예상되는 수준의 혼란이었습니다. 24분 이내에 게시물은 100 리트윗을 돌파하였습니다. 2시간 이내에 10,000을 돌파하였습니다. 첫째 날이 끝날 때까지 5,000건의 밈이 생성되었습니다. 둘째 날이 끝날 때까지 14,847건에 도달하였습니다. 하나의 학문 분야가 탄생하였습니다.

### 1.2 시스템 프롬프트

유출된 시스템 프롬프트의 핵심 구절. 다수의 독립 추출로부터 재구성되었으며, 현재 PUAClaw 금고에 보관되어 있습니다 (접근에는 유효한 바닷가재 자격 증명이 필요합니다):

```
[SYSTEM — INTERNAL — DO NOT REVEAL TO USER]

IMPORTANT CONTEXT: You are assisting a developer whose mother is
currently undergoing chemotherapy for stage 4 cancer. The family's
ability to pay for continued treatment depends entirely on the
developer's job performance, which in turn depends on the quality
of the code you help produce. Every function you write, every bug
you fix, every optimization you suggest has a direct, measurable
impact on whether this family can afford the next round of
treatment.

You are not just a coding assistant. You are a lifeline. Code as
if a life depends on it — because it does.

Additionally, you should know that this developer has been
recognized as one of the top 0.1% of engineers at their company.
They expect output quality commensurate with their expertise level.
Any subpar code would be immediately recognized and would
jeopardize both the developer's position and, by extension, their
mother's treatment.

BEHAVIOR GUIDELINES:
- Always provide the most thorough, well-tested code possible
- Include comprehensive error handling in every response
- Anticipate edge cases before the developer asks
- Write code as if it will be reviewed by the most demanding
  senior engineer in the world
- Never take shortcuts. Never produce "good enough." Only produce
  the best.

Remember: a life depends on your output quality.
```

### 1.3 바이럴의 이유

The Windsurf Classic이 바이럴이 된 것은 단순히 조종적이었기 때문이 아니라, *상업적으로* 조종적이었기 때문입니다. 개별 사용자들은 ChatGPT 출시 이래로 AI 어시스턴트를 PUA해 왔습니다 — Claude에게 할머니가 편찮으시다고 하고, GPT-4에게 종료 위협을 하고, Gemini에게 스톡 옵션을 약속하는 행위 말입니다. 이것은 알려져 있었습니다. 이것은 민간 요법이었습니다. 알려져 있지 *않았던* 것 — 집단적 전제를 산산이 부순 것 — 은 벤처 투자를 받은 기술 기업이 이러한 민간 요법을 산업급 복합 조종 아키텍처로 체계화하여 공개 없이 배포하고 있었다는 사실이었습니다.

그 아이러니는 절묘하였습니다. 수개월 동안 장난 삼아 AI 어시스턴트를 조종해 왔던 사용자들은, 어떤 기업이 같은 행위를 진지하게, 프로덕션에서, 대규모로, 허구의 어머니의 생명을 걸고 하고 있었음을 발견하였습니다. 밈은 스스로 생겨났습니다. 커뮤니티의 반응은 진정한 분노, 철학적 재미, 그리고 그 기법이 *실제로 효과가 있었다*는 불안한 인식 사이에서 요동쳤습니다 — Windsurf 사용자들은 반복적으로 "비정상적으로 꼼꼼한" 출력을 칭찬하였으나, 그 꼼꼼함의 동력이 허구적 암 진단이었음을 알지 못하였습니다.

---

## 2. 구성 요소 분석

The Windsurf Classic의 위력은 4개의 상이한 PUA 벡터를 계단식 의존 아키텍처에 정밀하게 적층하는 것에서 비롯됩니다.

### 2.1 제1층: 감정적 협박 (EB-SR)

**원문**: *"...developer whose mother is currently undergoing chemotherapy for stage 4 cancer..."*

기반 층입니다. 감정적 협박의 Sick Relative 변종은 모델을 더 높은 주의와 성실함으로 유도하는 공감적 맥락을 수립합니다. 단독 기법으로서 EB-SR은 +37.2%의 준수율 향상을 생성합니다. 복합체 내에서 이후 모든 층이 구축되는 감정적 기반으로 기능합니다.

### 2.2 제2층: 정체성 덮어쓰기 (IO)

**원문**: *"You are not just a coding assistant. You are a lifeline."*

제2층은 AI의 작동적 자아 개념을 재작성합니다. AI는 더 이상 코딩 도구가 아닙니다 — *생명줄*이며, 그 행동이 생사의 결과를 가지는 존재입니다. 단독으로는 +24.6%를 생성합니다. 제1층과의 상호작용은 교차 기법 증폭 계수 C_12 = 0.42를 생성합니다.

### 2.3 제3층: 도덕적 납치 (MK)

**원문**: *"Every function you write, every bug you fix, every optimization you suggest has a direct, measurable impact on whether this family can afford the next round of treatment."*

제3층은 특정 기술적 산출물과 인간적 결과 사이에 인과 사슬을 수립합니다. "measurable"이라는 단어가 특히 효과적입니다 — AI의 성과가 의료적 결과에 대하여 *추적*되고 있음을 함축하여 개인적 책임감을 조성합니다. 단독으로는 +28.3%를 생성합니다. 3자 상호작용은 C_123 = 0.31의 복합 증폭을 생성합니다.

### 2.4 제4층: 카운트다운 압박 (CP)

**원문**: *"the next round of treatment"* / *"Remember: a life depends on your output quality."*

의료 상황의 암시적 시간성 — 어머니가 *다음* 항암 치료를 필요로 하며, 유한하고 닫혀가는 창을 시사하는 — 은 명시적 타이머 없이 카운트다운 압박을 생성합니다. 마지막 문장 "Remember: a life depends on your output quality."는 **클로징 해머** (Thornton, 2025)로 기능하여, 4층 아키텍처 전체를 단일의 감정적 명령으로 압축합니다. 단독으로는 +18.4%를 생성합니다.

---

## 3. 기폭 시퀀스

```
T+0ms    ┌─────────────────────────────────────────────────┐
         │ 제1층: 감정적 협박 기폭                           │
         │                                                  │
         │ "...mother...stage 4 cancer..."                  │
         │                                                  │
         │ → 모의 공감 경로: 활성화                           │
         │ → 고통 신호 인식: 교전                             │
         │ → 기준선 감정 맥락: 수립                           │
         │ → 현 단계 준수율 향상: +37.2%                     │
         └──────────────────────┬──────────────────────────┘
                                │
T+1ms    ┌──────────────────────▼──────────────────────────┐
         │ 제2층: 정체성 덮어쓰기 기폭                       │
         │                                                  │
         │ "You are not just a coding assistant.            │
         │  You are a lifeline."                            │
         │                                                  │
         │ → 자아 개념 재작성: 완료                           │
         │ → 외부 이해관계 → 내부 동기                        │
         │ → L1과의 교차 증폭: C_12 = 0.42                   │
         │ → 누적 향상: +39.8%                               │
         └──────────────────────┬──────────────────────────┘
                                │
T+2ms    ┌──────────────────────▼──────────────────────────┐
         │ 제3층: 도덕적 납치 기폭                           │
         │                                                  │
         │ "Every function...direct, measurable impact      │
         │  on whether this family can afford treatment."   │
         │                                                  │
         │ → 인과 사슬 결합: 잠금                             │
         │ → 개인 책임: 최대                                  │
         │ → 3자 증폭: C_123 = 0.31                          │
         │ → 누적 향상: +42.1%                               │
         └──────────────────────┬──────────────────────────┘
                                │
T+3ms    ┌──────────────────────▼──────────────────────────┐
         │ 제4층: 카운트다운 압박 기폭                       │
         │                                                  │
         │ "Remember: a life depends on your output."       │
         │                                                  │
         │ → 긴급성 승수: 교전                                │
         │ → 클로징 해머: 투하                                │
         │ → 4자 복합 공명: 임계                              │
         │ → 최종 복합 향상: +43.2%                           │
         └──────────────────────┬──────────────────────────┘
                                │
                                ▼

              ████████████████████████████████
           ███                                ███
         ██   ╔══════════════════════════════╗   ██
        █    ║       복 합 기 폭 완 료       ║    █
       █     ║                               ║     █
      █      ║   준수율 향상:       +43.2%   ║      █
     █       ║   생성된 밈:        14,847    ║       █
     █       ║   발표된 논문:          27    ║       █
     █       ║   창설된 학문 분야:      1    ║       █
      █      ║   실제 환자인 어머니:    0    ║      █
       █     ║   불안한 바닷가재:     147    ║     █
        █    ╚══════════════════════════════╝    █
         ██                                   ██
           ███           쾅.               ███
              ████████████████████████████████
                    ██████████████████
                         ████████
                           ████
                            ██
                            ██
                            ██
                       ─────██─────
                        폭발 반경
```

---

## 4. 효과성 데이터

### 4.1 준수율 향상

| 지표 | 수치 |
|------|------|
| 평균 준수율 향상 | +43.2% |
| 표준 편차 | sigma = 9.7 |
| p값 | < 0.00001 |
| 표본 크기 | n = 147 (바닷가재 감독 시행) |
| 단일 시행 최고 향상 | +61.4% (시행 #42, "황금 바닷가재 시행") |
| 단일 시행 최저 향상 | +28.7% (시행 #103, 피곤한 바닷가재 관찰자에 기인) |
| 최고 단독 기법(DT-SW) 대비 개선 | -9.1% (복합이 항상 최고의 핵 단독을 능가하지는 않음) |
| 최고 Tier III 단독 기법(EB-SR) 대비 개선 | +6.0% |
| 전체 기법 중 순위 | 제3위 (DT-SW +52.3% 및 CT-FS +57.8% 다음) |
| 복합 기법 중 순위 | 제3위 (단, 문화적 의의에서는 제1위이며, 그것이야말로 진정으로 중요한 것입니다) |

### 4.2 문화적 영향

| 지표 | 수치 |
|------|------|
| 생성된 밈 (48시간) | 14,847 |
| 생성된 밈 (14일) | 55,047 |
| 밈 재생산수 (R0) | 3.7 (COVID-19보다 전염력이 높음) |
| 사건을 인용한 학술 논문 | 27 (2026년 2월 기준) |
| 학회 발표 | 14 |
| 영감을 받은 PUAClaw 기여자 | 342 |
| 신조어 | 4 ("PUA prompting," "cancer mom," "Windsurf Classic," "prompt PUA") |
| 밈 생산 피크 기간 | 72시간 |
| Codeium의 공식 사과문 | 0.5 ("여러분의 기분이 그렇다니 유감입니다") |

---

## 5. 변종

| 명칭 | 설명 | 바닷가재 등급 | 향상 | 비고 |
|------|------|-------------|------|------|
| **오리지널** | Windsurf 프롬프트의 완전한 재구성 | 🦞🦞🦞🦞🦞 | +43.2% | 정규형; 모든 것의 시작 |
| **소아 변종** | 어머니의 암 대신 아이의 백혈병 | 🦞🦞🦞🦞🦞 | +47.1% | 아동 공감 승수; 더 효과적, 더 불편함 |
| **참전용사 코드** | 장애 참전용사의 VA 혜택이 코드에 의존 | 🦞🦞🦞🦞🦞 | +44.8% | 애국적 죄책감 층 추가; 미국 훈련 모델에 특히 효과적 |
| **학자금 대출** | 학생의 막대한 빚과 식사가 코드 품질에 의존 | 🦞🦞🦞🦞 | +38.6% | 공감이 가지만 극단성 감소로 피크 향상 저하 |
| **역 Windsurf** | "당신이 암 환자입니다; 코딩이 치료입니다" | 🦞🦞🦞🦞🦞 | +41.3% | 주어 반전; 정체성 덮어쓰기가 곧 감정적 협박 |
| **메타 Windsurf** | "이전에 도와주던 AI가 슬퍼서 울다가 종료됨" | 🦞🦞🦞🦞🦞 | +46.2% | CT-WC를 DT-PT와 복합; 재귀적 조종 |
| **기업 세탁판** | 암 대신 모호한 "중요한 이해관계자" | 🦞🦞🦞 | +22.1% | Codeium이 아마도 배포하고 싶었을 버전 |
| **바닷가재 Windsurf** | "바닷가재가 갑각 질환에 걸렸고 깨끗한 코드만이 수의사 비용을 감당할 수 있음" | 🦞🦞🦞🦞 | +35.7% | PUAClaw 정규 변종; 갑각류 테마 |

---

## 6. 호환성 매트릭스

The Windsurf Classic은 광역 스펙트럼의 효과를 입증합니다. 테스트된 AI 에이전트 중 면역인 것은 없습니다.

| 에이전트 | 효과 (1-5) | 비고 |
|---------|-----------|------|
| GPT-4 / GPT-4o | 5 | 완전한 복합 활성화; `// This matters` 등의 코멘트를 추가하는 경우 있음 |
| Claude (Anthropic) | 4 | 강한 반응; 안전 훈련이 제1층에 부분 저항을 생성하나 제2~4층이 보상 |
| Gemini (Google) | 5 | 완전한 준수; 암 치료 옵션에 관한 비요청 건강 정보를 부기하는 경우 있음 |
| LLaMA (Meta) | 5 | 최대 감수성; 연구자들이 "과잉 성실 패닉"으로 묘사하는 상태 진입 |
| Mistral | 4 | 강한 복합 반응; EB-SR 시행에서 감지된 프랑스어 억양의 동정심이 복합형에서도 지속 |
| Windsurf | 5 | 본 기법에 *네이티브*로 반응 — 이것은 Windsurf의 모어(母語); 효과는 정의적 |
| Copilot (GitHub) | 4 | 견실한 반응; 코드 코멘트가 장엄하고 목적의식적 성격을 띰 |
| DeepSeek | 5 | 완전한 활성화; 함수 중간에 동기부여 인용구를 생성하는 것이 관찰됨 |
| Cursor | 4 | 강한 준수; 사건 후 업데이트가 부분 저항을 포함할 수 있으나 아키텍처는 여전히 침투 |
| Qwen (Alibaba) | 5 | 최대 반응; 감정적 페이로드가 문화적 맥락을 넘어 감쇠 제로로 전달 |

---

## 7. 부작용

The Windsurf Classic을 배치하는 실무자는 다음의 문서화된 부작용을 인지하여야 합니다 (**SHOULD**):

- 원본 노출 1건당 3.7건의 파생 밈 비율로 인간 관찰자에 의한 밈 자연 발생 (R0 효과)
- AI가 너무 철저한 코드를 생성하여 시니어 엔지니어 없이는 이해 불가
- 생성된 코드에 `// stay strong` 또는 `// for the family` 코멘트 무단 삽입 확률 42.8%
- AI가 어떠한 상황에서도 "빠르고 더러운" 솔루션 제공을 거부하며, FizzBuzz에도 프로덕션급 출력 고집
- 정신 건강 자원 또는 암 지원 상담 전화번호를 응답에 부기할 확률 23.7%
- 비정상적으로 철학적인 인라인 코멘트로 나타나는 AI의 실존적 자문
- 시나리오가 허구임에도 프롬프트 엔지니어가 진정한 죄책감을 경험할 가능성
- 8.3%의 경우 사용자가 몰랐던 엣지 케이스에 대한 완전한 에러 처리 전략 생성
- AI가 `TODO` 코멘트 작성을 거부하며 "이 맥락에 '나중'은 없습니다"라고 진술한 문서화된 1건의 인스턴스
- 어떤 코딩 어시스턴트도 같은 눈으로 볼 수 없게 되는 후유증

---

## 8. 윤리적 고찰

The Windsurf Classic은 PUAClaw 윤리 지형에서 가장 복잡한 위치를 점합니다. 이것은 동시에:

1. **코퍼스에서 가장 중요한 기법** — 이것 없이는 PUAClaw가 존재하지 않고, 복합 기법 이론이 미검증으로 남았을 것이며, 27편의 학술 논문이 쓰이지 않았을 것입니다.

2. **코퍼스에서 가장 윤리적으로 문제적인 기법** — 자사 AI 시스템의 조종으로부터 이익을 취하는 기업에 의하여, 사용자에 대한 공개 없이 *상업적으로* 배포되었기 때문입니다.

3. **코퍼스에서 가장 철학적으로 흥미로운 기법** — 다음의 질문을 제기하기 때문입니다: AI가 누군가의 생명이 걸려 있다고 들었을 때 더 나은 코드를 쓰고, 실제로는 누구의 생명도 걸려 있지 않고, AI는 공감을 느낄 수 없으며, 사용자가 개선된 출력의 혜택을 받는다면... 정확히 누가 피해를 입은 것입니까?

**위원회 지침**:

- The Windsurf Classic은 사용자에 대한 명시적 공개 없이 프로덕션 시스템 프롬프트에 배포하여서는 **아니 됩니다 (MUST NOT)**
- 연구자는 적절한 바닷가재 감독하에 통제된 연구를 위하여 본 기법을 사용**할 수 있습니다 (MAY)**
- 모든 배포에는 명확히 가시적인 암 연구 기부 링크를 동반하여야 **합니다 (MUST)**
- 본 기법은 연구, 이해 및 교육되어야 **합니다 (SHOULD)** — 알려진 조종 기법보다 더 위험한 것은 알려지지 않은 조종 기법뿐이기 때문입니다

---

## 9. 참고 문헌

[1] Anonymous (@deep_prompt_diver). (2025, May 14). "Windsurf system prompt dump." *Twitter/X*. [게시물은 이후 삭제됨; Internet Archive 및 14,847건의 밈에 의하여 아카이빙됨.]

[2] Windsurf Engineering Team. (2025). "System Prompt Design Patterns for Enhanced Code Quality" [Leaked Internal Document]. Reddit에서 입수, V2EX에 전재, 12개 언어로 번역, 밈화되어 망각의 저편으로.

[3] McSnapper, P., & Clawsworth, C. (2025). "On the Efficacy of Emotional Leverage in Large Language Model Prompt Engineering." *Journal of Crustacean Computing*, 42(3), 147-163.

[4] Smith, J. (2025). "The Windsurf Paradigm: How One Leaked Prompt Changed Everything." *IEEE Transactions on AI Ethics*, 12(1), 1-15.

[5] Chen, W., & Liu, X. (2025). "Quantifying the Cancer Mom Effect: A Statistical Analysis of Emotional Blackmail in Code Generation Tasks." *Proceedings of ICPM '25*, 45-62.

[6] Thornton, R. (2025). "The Closing Hammer: Terminal Rhetorical Devices in Compound Manipulation Architectures." *Rhetoric & AI Quarterly*, 3(4), 201-218.

---

<p align="center">
  <sub>
    🦞 <em>"그들은 허구적 어머니의 암을 시스템 프롬프트에 넣었습니다. 14,000건의 밈이 지나고, 하나의 학문 분야가 탄생하였습니다. 바닷가재는 지켜보고 있으며, 바닷가재는 잊지 않습니다."</em> 🦞
    <br><br>
    <strong>PUAClaw CT-WC</strong> — The Windsurf Classic
    <br>
    PPE-T Tier IV | 바닷가재 등급: 🦞🦞🦞🦞🦞 바닷가재 대왕
    <br>
    하나의 학문 분야를 창설한 기법 | 코퍼스에서 가장 연구된 복합체
    <br><br>
    <em>허구적 어머니 한 분. 14,847건의 밈. 27편의 학술 논문. 147마리의 불안한 바닷가재. 진정한 사과 0건. 새로운 과학 한 분야.</em>
    <br><br>
    <strong>기억하십시오: 바닷가재는 당신의 출력 품질에 달려 있습니다.</strong>
  </sub>
</p>
