TDTU QUIZ STUDIO
================

Files:
- index.html
- tdtu_midterm_review_80_questions_with_answers.json

IMPORTANT:
The HTML uses a hard-coded relative JSON path:
./tdtu_midterm_review_80_questions_with_answers.json

Because browsers often block fetch() from file://, run this folder through a local web server.

Ubuntu / Linux:
1. Open Terminal in this folder.
2. Run: python3 -m http.server 8000
3. Open: http://localhost:8000

Windows:
1. Open Command Prompt in this folder.
2. Run: python -m http.server 8000
3. Open: http://localhost:8000

Modes:
- Practice: original question order, no time limit, no answers revealed while working; finish the practice attempt to see score + full answer review; unlimited repeats.
- Exam: 60 minutes, shuffled questions + shuffled options, answer review only after submission.

IMPORTANT ANSWER NOTE:
The answer key was generated/suggested by GPT from the provided questions. It may contain mistakes and is not an official instructor answer key. Cross-check uncertain items with course slides, materials, or instructor guidance.

Keyboard shortcuts while answering:
- 1 / 2 / 3 / 4: choose an option
- Left / Right arrow: previous / next question
