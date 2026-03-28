# playbook.md → opus.md 리네이밍

- date: 2026-03-28
- tags: playbook, naming, opus

## 맥락

playbook.md라는 파일명이 AI 에이전트 코딩 규칙 문서의 성격에 맞지 않고, 한글(7자)·영문(11자) 모두 타이핑이 길었다. 바이브코딩/에이전트 코딩 생태계에서 크로스 프로젝트 최상위 문서에 대한 관행적 네이밍 규칙은 아직 없음을 확인.

## 검토한 후보

| 후보 | 근거 | 탈락 사유 |
|---|---|---|
| OPS.md | operations 약어, 짧음 | 문서 성격이 "운영"보다 "규칙" |
| RULES.md | 업계에서 에이전트 규칙 파일에 널리 사용 | 같은 레포에 common-rules.md 존재, 혼동 |
| HQ.md | headquarters, 2음절 | 모호함 |
| DISPATCH.md | 라우팅 역할 표현 | 한글 4음절, 교훈·규칙 등 정적 내용 포함 |
| OPUS.md / opus.md | 읽는 주체가 곧 이름, CLAUDE.md와 대칭 | 채택 |

## 결론

- playbook.md → opus.md 리네이밍
- 레포명 leftjap/playbook은 유지 (URL 변경 영향 범위가 큼)
- 수정 대상: playbook 레포 내부 10개 파일. 다른 레포(docs, gym, study, keep) 수정 불필요 — PowerShell 전수 검색으로 확인

## 후속

- 세션 시작 시 업로드 파일명이 opus.md로 변경됨
- opus.md 내부의 자기 참조, common-rules.md·backlog.md 등의 참조가 모두 opus.md로 치환됨
