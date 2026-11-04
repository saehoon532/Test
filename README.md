# Codex 웹 스킬

Codex 웹에서 이 저장소로 새 작업을 시작하면 `.agents/skills/`의 스킬을 사용할 수 있습니다.

| 스킬 | 원본 저장소 |
| --- | --- |
| `workers-best-practices` | [cloudflare/skills](https://github.com/cloudflare/skills) |
| `agent-browser` | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) |
| `frontend-design` | [anthropics/skills](https://github.com/anthropics/skills) |
| `find-skills` | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| `systematic-debugging` | [obra/superpowers](https://github.com/obra/superpowers) |
| `obsidian-markdown` | [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) |
| `remotion-best-practices` | [remotion-dev/skills](https://github.com/remotion-dev/skills) |

예: 작업 지시에 `$frontend-design` 또는 `$systematic-debugging`을 포함하세요.

스킬 원문과 지원 파일을 함께 보관했습니다. 원본 커밋과 파일 검증 정보는 `.agents/skill-sources.json`을 참고하세요. 원본에서 제공한 라이선스는 각 스킬 폴더에 있습니다.

스킬은 작업 지침입니다. `agent-browser` CLI·브라우저 런타임, Remotion 및 Wrangler 등은 실제 작업 환경에 별도로 설치해야 합니다. 이 변경은 해당 도구의 설치나 서비스 연결을 수행하지 않습니다.

공식 문서: [스킬 만들기](https://learn.chatgpt.com/docs/build-skills), [Codex 클라우드 환경](https://learn.chatgpt.com/docs/environments/cloud-environments).
