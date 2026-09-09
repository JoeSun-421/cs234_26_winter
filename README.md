<<<<<<< HEAD
# Stanford CS234: Reinforcement Learning (Winter 2026)

Downloaded from the official Stanford CS234 course site on 2026-09-10.

## Directory layout

- `lectures/`: post-class lecture slides only.
- `assignments/assignment01/`: Assignment 1 questions and extracted `code/` project.
- `assignments/assignment02/`: Assignment 2 questions and extracted `assignment2_starter_code/` project.
- `assignments/assignment03/`: Assignment 3 questions and extracted `starter_code/` project.

## Lecture topic map

- Lectures 1-4: introduction, tabular MDP planning, policy evaluation, and Q-learning.
- Lectures 5-7: policy gradients.
- Lectures 7-8: imitation learning, human input, and batch RL.
- Lectures 9-12: data-efficient RL, including bandits and exploration.
- Lecture 10: ethics and society guest material is included in the post-class PDF.
- Lectures 13-14: Monte Carlo tree search and conquering Go.
- Guest lecture: Shane Gu, World of World Modeling.

## UV environments

Each extracted starter-code project was initialized with `uv init` and has its own `pyproject.toml`, `.python-version`, and `.venv` where dependency installation succeeded.

- Assignment 1: `assignments/assignment01/code/` (Python 3.10)
- Assignment 2: `assignments/assignment02/assignment2_starter_code/` (Python 3.9; see the original README for the legacy `gym==0.21` install note)
- Assignment 3: `assignments/assignment03/starter_code/` (Python 3.10)

Assignment 2 uses `pip==23.0` inside the uv-created environment because current uv rejects the invalid historical metadata in `gym==0.21`; all dependencies from its original `requirements.txt` were installed successfully. Consequently, A2 has no `uv.lock`, while A1 and A3 do.

## Official sources

- Course home: https://web.stanford.edu/class/cs234/
- Lecture materials: https://web.stanford.edu/class/cs234/modules.html
- Assignments: https://web.stanford.edu/class/cs234/assignments.html
- Course project: https://web.stanford.edu/class/cs234/project.html

The official page has no downloadable `lecture10pre.pdf`; only the post-class version is linked. Assignment 3 starter code is hosted by Google Drive through the official course page. The local `source/` page archive was intentionally removed after sorting the files.
=======
# cs234_26_winter
A repo that contains cs234 lecs, assignments, and projects
>>>>>>> origin/main
