# Professor Skill for Claude Code

An advanced AI teaching assistant skill that behaves like a strict but helpful university professor.

## Features

- **4 Modes**: Lecture, Exam, Prediction, Practice
- **Star Rating System**: Labels concepts by exam importance (⭐ to ⭐⭐⭐)
- **Interactive MCQs**: Button-based questions with navigation
- **Memory Tracking**: Tracks strong/weak/critical areas per session
- **Strict Interaction Rules**: Never skips steps, never reveals answers early

## Installation

### Option 1 — Project-level (applies to one project)

1. In your project root, create the folder `.claude/skills/` if it doesn't exist.
2. Copy `professor.md` into `.claude/skills/professor.md`.

### Option 2 — Global (applies to all your projects)

1. Open your global Claude Code config folder:
   - **Windows**: `%APPDATA%\Claude\skills\` or `C:\Users\<you>\.claude\skills\`
   - **macOS / Linux**: `~/.claude/skills/`
2. Copy `professor.md` into that folder.

> If the `skills/` folder does not exist, create it manually.

## Usage

1. Upload or paste your course materials (lecture notes, PDFs, GitHub repo link, etc.) into the conversation.
2. Type:

```
lecture me
```

3. Select a mode when prompted:

```
1. Lecture Mode
2. Exam Mode
3. Prediction Mode
4. Practice Mode
```

4. Follow the professor's instructions.

## Modes

| Mode | What it does |
|---|---|
| **Lecture** | Teaches topic with structure, examples, and MCQs |
| **Exam** | Generates a full midterm or final exam |
| **Prediction** | Predicts what topics are likely to appear in exams |
| **Practice** | Generates exercises with increasing difficulty |

## Notes

- The skill works ONLY with materials you provide — it does not hallucinate outside given content.
- If materials are missing or unclear, it will ask before proceeding.
- MCQ navigation is fully interactive: you must answer before moving forward.

## License

MIT — free to use, modify, and share.
