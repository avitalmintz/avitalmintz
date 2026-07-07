## Avital Mintz

I build local-first, privacy-focused tools for macOS — software that does real
work entirely on your own machine — alongside production AI applications.

Most of what's here runs on-device: no cloud, no accounts, nothing leaving your
laptop. I care about tools that are fast, honest about their limits, and yours.

### Local-first macOS tools

- **[granola-local](https://github.com/avitalmintz/granola-local)** — AI meeting
  notes that run 100% on your Mac. A free, open-source reimplementation inspired
  by Granola: on-device transcription, your rough bullets rewritten into
  structured notes. *Python*
- **[gesture-control](https://github.com/avitalmintz/gesture-control)** — Control
  your Mac with your hands using just the built-in camera, on a MediaPipe hand
  skeleton driving several apps. *Python · OpenCV*
- **[clipsplit](https://github.com/avitalmintz/clipsplit)** — Split a screen
  recording into clean clips wherever the content changes, each auto-named from
  the text on screen via on-device OCR. *Python · ffmpeg · Apple Vision*
- **[freshdoc](https://github.com/avitalmintz/freshdoc)** — Find the notes in a
  markdown folder that have gone stale, contradict a newer note, or link to
  things that no longer exist. Deterministic, zero-ML by default. *Python*

### AI applications

- **[forensic-ai-report-assistant](https://github.com/avitalmintz/forensic-ai-report-assistant)**
  — Production AI application that helps forensic psychologists draft psychiatric
  evaluation reports. *Claude · Amazon Bedrock · AWS Lambda · Cognito · Amplify*
- **[shelf-life-app](https://github.com/avitalmintz/shelf-life-app)** —
  Mobile-first screenshot organizer with AI categorization. A React PWA with a
  Capacitor iOS build, a native Share Extension, and local-first storage.
  *TypeScript*

### Building with

`Python` · `TypeScript` · `React` · `Whisper` · `OpenCV` · `Apple Vision` ·
`AWS (Bedrock, Lambda, Cognito, Amplify)` · `local LLMs (Ollama)`
