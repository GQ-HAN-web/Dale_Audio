---
copilot-command-context-menu-enabled: false
copilot-command-slash-enabled: false
copilot-command-context-menu-order: 1090
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Generate glossary]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Glossary generation workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Generate glossary]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Create a glossary of important terms, concepts, and phrases from {}. Format each entry as "Term: Definition". Sort entries alphabetically. Return only the glossary.