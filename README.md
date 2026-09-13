# AI Voice Interviewer

An AI-powered voice-based interview practice tool that conducts realistic, interactive interviews.

## Features

- **Voice-based interaction** — speaks questions aloud and listens to your spoken answers
- **Dynamic question generation** — no fixed question lists; the AI adapts based on your responses
- **Two difficulty modes**:
  - **Beginner** — starts with fundamentals, gradually increases difficulty
  - **Ready for Interview** — realistic professional interview from the start
- **Adaptive difficulty** — adjusts based on your performance in real time
- **Comprehensive assessment** — detailed performance report with scores, strengths, weaknesses, and recommendations

## How to Use

1. Open the [website](https://abiraami279.github.io/ai-interview-agent/)
2. Get a **free API key** from either:
   - **Groq**: [console.groq.com/keys](https://console.groq.com/keys) — runs open-source Llama 3.3 70B
   - **Google Gemini**: [aistudio.google.com/apikey](https://aistudio.google.com/apikey) — runs Gemini 3.1 Flash-Lite
3. Enter your name, the role you're interviewing for, and your level
4. Click the settings (⚙️) icon and paste your key — the app auto-detects Groq vs Gemini (supports both new `AQ.Ab...` and legacy `AIza...` Gemini key formats)
5. Start the interview — speak naturally, and the AI will guide the conversation
6. End the interview to receive your detailed performance assessment

## Tech

- Pure HTML/CSS/JavaScript — no backend, no dependencies
- Web Speech API for voice input/output
- **Groq API** (Llama 3.3 70B, open-source) via OpenAI-compatible endpoint
- **Google Gemini API** (Gemini 3.1 Flash-Lite) via native `generateContent` endpoint — works with both new `AQ.` auth keys and legacy `AIza` keys
- Auto-detects your API key provider — just paste and go

## Browser Support

Best experienced in **Google Chrome** or **Microsoft Edge** (Web Speech API support required).
