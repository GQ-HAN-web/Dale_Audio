---
copilot-command-context-menu-enabled: false
copilot-command-slash-enabled: false
copilot-command-context-menu-order: 1110
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Rewrite as tweet]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Social post rewriting workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Rewrite as tweet]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Rewrite {} as a single tweet with these requirements:
    1. Maximum 280 characters
    2. Use concise, impactful language
    3. Maintain the core message
    Return only the tweet text.