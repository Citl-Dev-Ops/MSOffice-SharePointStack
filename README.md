# CITL Factbook Assistant (Audio + RAG)

**CITL Engineers:** Abdo Mohamed · Wahaj al Obid · Mason Jones  
**Offline Classroom Tool:** Local LLM (Ollama) + RAG over instructor documents + classroom audio capture + transcription.

![Combined Factbook + Transcription GUI](docs/assets/combined_gui.png)

## What this is
A Windows-friendly desktop assistant for classrooms that combines:
- **Local LLM chat** via Ollama (privacy-first, works offline)
- **RAG (retrieval)** over instructor-provided `.txt` documents (“Factbooks”)
- **Classroom audio capture + transcription** to create searchable notes

## Why it matters in classrooms
- Keeps data **in-house** (privacy and reliability)
- Lets instructors drop in course documents and get **fast, local Q&A**
- Captures lecture audio → transcript → searchable notes for study support

## Quick start (Windows)
1) Install and start Ollama, then verify:
   - `ollama serve`
   - `ollama list`

2) From repo root:
   - `.\.venv\Scripts\Activate.ps1`
   - `python .\factbook-assistant\factbook_assistant_gui.py`

## Using the GUI
- **Add Text Files…**: add `.txt` docs to the data folder
- **Index Selected / Index All**: build the retrieval index
- Ask questions in **Factbook Query**
- Use **Audio Capture + Transcription** to record and transcribe lecture audio

## Credits
See `CREDITS.md` for contributor acknowledgements and roles.

## Citation
Use GitHub “Cite this repository” (powered by `CITATION.cff`).
