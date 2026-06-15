---
copilot-command-context-menu-enabled: true
copilot-command-slash-enabled: true
copilot-command-context-menu-order: 1050
copilot-command-model-key: ""
copilot-command-last-used: 0
relationships:
  - type: supports
    target: "[[Obsidian Copilot workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Emojify]]"
    status: active
    note: "This prompt supports repeatable AI-assisted note operations."
  - type: commits-to
    target: "[[Text style enhancement workflow]]"
    evidence:
      - "[[copilot/copilot-custom-prompts/Emojify]]"
    status: proposed
    note: "This prompt defines a repeatable AI note-processing action."
---

Add relevant emojis to enhance {}. Follow these rules:
    1. Insert emojis at natural breaks in the text
    2. Never place two emojis next to each other
    3. Keep all original text unchanged
    4. Choose emojis that match the context and tone
    Return only the emojified text.