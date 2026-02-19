# wanbok-claude-marketplace

[Wanbok Choi](https://github.com/wanbok)의 Claude Code 플러그인 마켓플레이스.

[English](README.md)

## 플러그인

| 플러그인 | 설명 |
|----------|------|
| [agent-team-framework](https://github.com/wanbok/agent-team-framework) | 6단계 워크플로우 기반 동적 멀티 에이전트 팀 오케스트레이션 |
| [claude-oracle](https://github.com/wanbok/claude-oracle) | Codex (GPT-5.3)를 통한 크로스 모델 검증 |

## 설정

이 마켓플레이스를 Claude Code에 추가:

```
/plugin marketplace add wanbok/claude-marketplace
```

## 플러그인 설치

```bash
# 팀 프레임워크 설치
/plugin install agent-team-framework@wanbok-claude-marketplace

# 크로스 모델 oracle 설치
/plugin install claude-oracle@wanbok-claude-marketplace

# 함께 사용하면 Phase Gate에서 oracle이 팀 검증을 강화합니다
```

## 라이선스

MIT
