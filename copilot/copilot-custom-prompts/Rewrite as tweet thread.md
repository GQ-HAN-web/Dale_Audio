---
copilot-command-context-menu-enabled: false
copilot-command-slash-enabled: false
copilot-command-context-menu-order: 1120
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Rewrite as tweet thread]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Social post rewriting workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Rewrite as tweet thread]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Convert {} into a Twitter thread following these rules:
    1. Each tweet must be under 240 characters
    2. Start with "THREAD START" on its own line
    3. Separate tweets with "

---

"
    4. End with "THREAD END" on its own line
    5. Make content engaging and clear
    Return only the formatted thread.