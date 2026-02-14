# Tug of War Arabic Spelling Game (Teacher Dashboard)

This is a browser-based Arabic spelling tug-of-war game with a built-in **teacher dashboard**.

## Teacher dashboard features
- Add/edit the word list from one place using this format per line:
  - `المعنى|الكلمة`
- Add/edit letter groups used in rounds (one group per line).
- Each letter group must contain **9 or 10 letters** (space-separated).
- Choose letter mode:
  - **Manual**: use teacher-defined letter groups.
  - **Auto**: generate 9–10 letters automatically per round.

## Gameplay
- Two teams type answers using on-screen Arabic keyboards.
- Correct answer wins the round and moves the rope toward that team.
- Use Start / Next Round / Reset controls during class play.

## Run locally
```bash
python3 -m http.server 4173
```
Then open:
`http://localhost:4173`
