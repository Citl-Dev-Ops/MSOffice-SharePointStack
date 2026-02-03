# GPT Anchor: Combined GUI Recovery (Stable)

**Anchor ID:** CITL-COMBINED-GUI-STABLE-2026-01-16

## Symptom
Wrong/older GUI opens (missing Factbook + Transcription integration).

## Fix checklist
1) Confirm you are in the correct repo:
   - CITL---Desktop-LLM-EZ-Install-Kits
2) Confirm entrypoint exists:
   - factbook-assistant\factbook_assistant_gui.py
3) Confirm it runs:
   - python -m py_compile .\factbook-assistant\factbook_assistant_gui.py
   - python .\factbook-assistant\factbook_assistant_gui.py
4) Confirm Ollama:
   - Test-NetConnection 127.0.0.1 -Port 11434
   - ollama list

## Screenshot placement
Save the modern combined GUI screenshot to:
docs/assets/combined_gui.png
and commit it so the front page shows the correct UI immediately.
