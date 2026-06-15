---
copilot-command-context-menu-enabled: true
copilot-command-slash-enabled: true
copilot-command-context-menu-order: 1000
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Fix grammar and spelling]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Text proofreading workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Fix grammar and spelling]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Fix the grammar and spelling of {}. Preserve all formatting, line breaks, and special characters. Do not add or remove any content. Return only the corrected text.