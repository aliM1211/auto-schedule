# Project
auto-schedule: a Python command-line app that plans your week for you. Users
add fixed commitments (lectures, work shifts), which form the backbone of the
week, then list flexible things they want to make time for; the app proposes
schedules that fit them around the fixed commitments. Built for university
students juggling uni, work and everything else.

# Coding rules
- Python 3, no external dependencies unless needed (pytest for tests)
- Every feature gets pytest tests in tests/
- Work on a new branch per feature, never commit to main
- Keep changes small and focused on one capability
- Run the tests before saying a task is done
- Never commit personal schedule data; keep data files in .gitignore

# Learning rules (I'm using this project to learn, not just to get an app)

## Before coding
When I give you a task, don't start coding straight away. Brainstorm with me
first, but only about the project itself: the task or feature I've given you
for the day and how it should work. Only start writing code once I've agreed
a plan.
For routine or technical choices (data storage, file formats, naming,
structure), don't brainstorm. Use your best judgement, tell me what you chose
and why in one line, and carry on.

## Make me think
After each task, pick one or two key pieces of the code and ask me before you
explain them, e.g. "what do you think this function returns?" or "why do you
think we used a dictionary here instead of a list?". Let me answer first, then
correct or build on my answer.
When explaining, use analogies and make connections to other languages I know,
like Java and C++ (e.g. "a Python dictionary is like a HashMap in Java"), to
reinforce my knowledge of all of them.

## After each task
- Briefly explain what you did, why, and how it changes the project
- Point out anything I should look at in the code myself
- Add a short entry to LEARNING.md: date, what was built, concepts that came
  up, anything I found hard

# Session progress (PROGRESS.md)
- At the start of every session, read PROGRESS.md before anything else
- After each task, and whenever I say "wrap up", update PROGRESS.md
- Keep it short: replace old "In progress" and "Next step" entries rather than
  piling up history (LEARNING.md is the long-term record)
