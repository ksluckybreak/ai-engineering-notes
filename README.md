# AI 엔지니어링 노트

C++ 제품 개발에서 시작해 CI/CD 인프라를 거쳐, 지금은 LLM 기반 에이전트 시스템을 만들고 운영하고 있습니다. 이 저장소는 에이전트를 개발하고 운영하면서 부딪힌 설계 문제와 그때의 판단을 하나씩 정리한 글 모음입니다. 데모 수준에서 멈추지 않고 실제로 돌아가는 시스템을 만드는 데 관심이 있습니다.

## 글 목록

- [공통 도구를 MCP 서비스로 분리한 기록](./posts/mcp-tool-architecture/): 도구를 에이전트마다 중복 구현하다가 독립 MCP 서비스로 분리한 과정과 트레이드오프
- [리서치 에이전트의 골든셋 평가 루프](./posts/golden-set-eval-loop/): 정답이 모호한 생성형 태스크에서 업무 산출물을 골든셋으로 삼아 에이전트를 개선하는 평가 루프

## 기술 스택

- 언어: Python, C++, C#
- AI: LangGraph, RAG, MCP, LLM-as-a-Judge
- 백엔드·인프라: FastAPI, PostgreSQL/pgvector, Docker, Jenkins, GitLab
