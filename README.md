# Research RIZZ

A standalone agent skill for researching useful connections between fields. It combines selected TRIZ tools with source reading, explicit mechanism transfer, practical experiments and room for a credible speculative idea.

All method instructions are contained in `SKILL.md`.

## Requirements

- An AI assistant that can read instructions and use the current conversation.
- No other skills, plugins, scripts, package installs, API keys or dedicated services.
- Browsing is optional. The assistant can work from supplied sources; without sources, it labels ideas as unverified hypotheses.
- Public references in the skill provide attribution and optional background. They are not runtime dependencies.

## Use

For Claude Code, place this folder at `~/.claude/skills/research-rizz/` and invoke `/research-rizz`.

For Codex, place it at `~/.codex/skills/research-rizz/` and invoke `$research-rizz`. The `agents/openai.yaml` file supplies optional display metadata.

For another assistant, provide the contents of `SKILL.md` as instructions and ask it to apply Research RIZZ to the current problem or research question.

An invocation alone uses the existing conversation. For a new conversation, describe the problem or question and any constraints.

## How it works

1. Establish the current question, ordinary approach and unresolved need.
2. Research mechanisms in other fields, including distant connections when exploration calls for them.
3. Explain the source-to-target mapping, required adaptation, evidence and limits.
4. Use the embedded TRIZ tools to develop concrete alternatives.
5. Challenge the claimed benefit and preserve a credible wildcard when useful.
6. Recommend an informative experiment or a better question to investigate.

The skill preserves the conversation's scope and permissions. A research request produces proposals; executing an experiment requires authorization for its actions.

## Contents

```text
research-rizz/
  SKILL.md
  README.md
  agents/
    openai.yaml
```

The package contains instructions and optional display metadata, with no executable code or telemetry. Context comes from the conversation and sources provided to the assistant. Any browsing uses the host assistant's existing tools and privacy settings.

## Method references

Research RIZZ combines TRIZ, Function-Oriented Search and analogical reasoning. Selected TRIZ principles are built into `SKILL.md`, along with links to the original methods and related implementations.
