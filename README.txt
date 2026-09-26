TDTU QUIZ STUDIO
================

Files:
- index.html
- tdtu_midterm_review_80_questions_with_answers.json
- tdtu-elearning-logo.png (official TDTU E-learning header logo)
- tdtu-footer-bg.png (official Moove/TDTU footer background)
- tdtu-default-avatar.png (official Moodle default avatar)

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
- TDTU exam room experience: Moodle/TDTU-style full-screen interface, 5 questions per page, 16 pages, 60-minute timer, question flags, answer clearing, navigation grid, autosave, and review after submission.

Official interface assets:
- Header logo source: https://elearning.tdtu.edu.vn/pluginfile.php/1/theme_moove/logo/1790297266/Brand-left-vi-1_0_0.png
- Footer background source: https://elearning.tdtu.edu.vn/theme/image.php/moove/theme/1790297266/footer-bg
- Default avatar source: https://elearning.tdtu.edu.vn/theme/image.php/moove/core/1790297266/u/f2
- Interface font: Poppins (the font used by the TDTU Moove theme)

IMPORTANT ANSWER NOTE:
The answer key was generated/suggested by GPT from the provided questions. It may contain mistakes and is not an official instructor answer key. Cross-check uncertain items with course slides, materials, or instructor guidance.

Keyboard shortcuts while answering:
- 1 / 2 / 3 / 4: choose an option
- Left / Right arrow: previous / next question
