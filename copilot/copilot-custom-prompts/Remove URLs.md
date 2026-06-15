---
copilot-command-context-menu-enabled: false
copilot-command-slash-enabled: false
copilot-command-context-menu-order: 1100
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Remove URLs]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Text cleanup workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Remove URLs]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Remove all URLs from {}. Preserve all other content and formatting. URLs may be in various formats (http, https, www). Return only the text with URLs removed.