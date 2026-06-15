---
copilot-command-context-menu-enabled: false
copilot-command-slash-enabled: false
copilot-command-context-menu-order: 1080
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Generate table of contents]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Table of contents workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Generate table of contents]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Generate a hierarchical table of contents for {}. Use appropriate heading levels (H1, H2, H3, etc.). Include page numbers if present. Return only the table of contents.