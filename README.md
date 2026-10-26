# socratic — 소크라테스 문답 스킬

Claude가 답 대신 **질문을 하나씩** 던져, 무언가가 "왜 있어야 하는지"를 사용자가 스스로 찾게 돕는 [Agent Skills](https://agentskills.io/specification) 형식의 스킬입니다. 문답은 한 문서에 그대로 기록합니다.

## 무엇을 하나

- **질문의 사다리:** 없애 보기 → 떼어 보기 → 대체재와 비교 → 비유로 흔들기 → 경계 묻기 → 사실과 맞대기
- **질문 규칙:** 한 번에 하나, 기대하는 답을 암시하지 않기, 한 말에서만 판단하기
- **기록 틀:** 출발점 · 문답 표(답은 한 말 그대로) · 드러난 것 · 열린 물음 · 이어지는 곳

자세한 내용은 [SKILL.md](socratic/SKILL.md)에 있습니다.

## 설치

`socratic` 폴더를 스킬 폴더에 복사합니다.

| 쓰는 곳 | 복사할 자리 |
|---|---|
| 내 컴퓨터의 모든 프로젝트 | `~/.claude/skills/socratic/` |
| 한 프로젝트만 | `<프로젝트>/.claude/skills/socratic/` |

```bash
git clone https://github.com/Frost0313z/socratic-inquiry-skill.git
cp -r socratic-inquiry-skill/socratic ~/.claude/skills/
```

## 쓰는 법

Claude Code에서 `/socratic`을 입력하거나(뒤에 탐구할 대상을 붙여도 됩니다 — `/socratic 이 앱은 왜 있어야 하나`), 이렇게 말하면 됩니다.

- "소크라테스 문답법으로 이 앱이 왜 있어야 하는지 탐구하자"
- "답 말고 질문만 해줘"

## 만든 배경

2026-10-24, 팀 프로젝트 앱이 존재하는 본질적인 이유를 소크라테스 문답으로 탐구하면서 반복된 질문 흐름과 기록 방식을 정리했습니다. 초안은 Claude(Claude Code)가 썼고, 한 번의 문답에서만 나온 것이라 **끝내는 조건은 아직 미정**입니다.

## 라이선스

[MIT](LICENSE)
