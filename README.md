# Memory Training Platform

A simple and interactive platform to help you remember trainee and trainer names.

## Features

### Trainee Mode
- **20 trainees** from B28 & B29 batches
- Filter by major (Cyber Security, Computer Science, Data Science, AI, etc.)
- Multiple choice mode (4 options)
- Spelling mode (type full name)
- Hint system (3 levels)

### Trainer Mode
- **82 trainers** from Gen 19-2 to 25-2
- Filter by generation (25-2, 25-1, 24-2, 24-1, etc.)
- Filter by position (Laboratory Assistant, Subject Coordinator Staff, etc.)
- Multiple choice mode
- Spelling mode
- Guess position mode

## How to Run

### Option 1: Using Python (Recommended)
```bash
cd memory-training-platform
python -m http.server 8000
```
Then open http://localhost:8000 in your browser.

### Option 2: Using Node.js
```bash
cd memory-training-platform
npx serve .
```

### Option 3: Using VS Code Live Server
1. Open the folder in VS Code
2. Install "Live Server" extension
3. Right-click on `index.html` and select "Open with Live Server"

### Option 4: Using XAMPP/WAMP
1. Copy the folder to `htdocs` (XAMPP) or `www` (WAMP)
2. Start Apache
3. Open http://localhost/memory-training-platform

## Data Summary

### Trainees (20 total)
| Batch | Count |
|-------|-------|
| B28   | 2     |
| B29   | 18    |

### Trainers by Generation (82 total)
| Generation | Count |
|------------|-------|
| 25-2       | 4     |
| 25-1       | 12    |
| 24-2       | 23    |
| 24-1       | 17    |
| 23-2       | 12    |
| 23-1       | 5     |
| 22-2       | 5     |
| 22-1       | 2     |
| 20-1       | 1     |
| 19-2       | 1     |

## Scoring System

- **Multiple Choice**: 10 points per correct answer
- **Spelling Mode**: 15 points per correct answer
- **With Hints**: Points reduced based on hint level used

## Tips

1. Start with multiple choice to familiarize yourself with faces and names
2. Progress to spelling mode for deeper memorization
3. Use hints sparingly - they reduce your score but help with learning
4. Practice by generation or major to focus on specific groups

---
Made with ❤️ for better memory training
