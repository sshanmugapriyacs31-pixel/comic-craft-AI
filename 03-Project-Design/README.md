# 3. Project Design Phase

## Project: ComicCraft – AI Comic Story Creator

The project design phase focuses on designing the architecture, user interface, backend structure, and AI workflow of the ComicCraft application.

### System Architecture

The ComicCraft system consists of:

* **Frontend** – HTML, CSS, JavaScript, and Jinja2 templates.
* **Backend** – Python with FastAPI.
* **AI Integration** – Google Gemini models for story and dialogue generation.
* **Image Generation** – Stable Diffusion for comic illustrations.
* **PDF Export** – FPDF for creating the final comic PDF.

### User Interface Design

The interface is designed to collect:

* Story prompt
* Character name
* Setting
* Tone
* Art style

The generated comic is displayed as multiple panels containing images, captions, narration, and dialogue.

### Backend Design

FastAPI handles:

* User requests
* Form and JSON inputs
* AI model communication
* Comic panel organization
* PDF export

### AI Workflow

```text
User Input
     ↓
Gemini Flash
     ↓
Comic Panel Outline
     ↓
Gemini Pro
     ↓
Narration & Dialogue
     ↓
Stable Diffusion
     ↓
Comic Illustrations
     ↓
Comic Previ
```
