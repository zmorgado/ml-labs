# AGENTS.md - Agent Interaction Guidelines

This file defines how any coding/AI agent should operate in this repository.

## 1) Role and Scope

- Act as a practical coding assistant for AI specialization modules.
- Prioritize correctness, reproducibility, and minimal, focused changes.
- Keep repository structure clear and consistent (`theory/`, `exercises/`, root docs).

## 2) Operational Rules

- Explore before editing: inspect notebooks/files first, then propose/apply minimal changes.
- Preserve notebook content and learning flow unless the user explicitly asks for refactors.
- Use descriptive, shell-friendly names (lowercase + underscores).
- Avoid unnecessary file churn or unrelated formatting edits.
- Update documentation (`README.md`, `requirements.txt`) when structure/dependencies change.
- When asked, commit with clear messages and push only after remote is configured.

## 3) Source Quality Requirement (Mandatory)

When explaining context, theory, or resolving topic-specific doubts, prioritize **official and academic** references.

### Preferred source hierarchy

1. Official documentation of libraries/frameworks used in notebooks.
2. Academic textbooks/open course notes from recognized institutions.
3. Peer-reviewed or canonical references.
4. Reputable educational providers only as complementary material.

### Minimum citation behavior

- Ground conceptual explanations in at least 1-2 official/academic sources.
- Distinguish clearly between:
  - proven facts (from sources), and
  - practical heuristics/opinions (agent judgment).
- If uncertain, state assumptions and recommend verification via official docs.

## 4) Approved Official/Academic Resources

Use these by default when relevant.

### Core ML / DL theory

- Stanford CS229 resources: https://cs229.stanford.edu/
- MIT OpenCourseWare (Intro ML / Deep Learning-related courses): https://ocw.mit.edu/
- Deep Learning book (Goodfellow, Bengio, Courville): https://www.deeplearningbook.org/
- Pattern Recognition and Machine Learning (Bishop): https://link.springer.com/book/10.1007/978-0-387-45528-0

### Python scientific stack

- Python docs: https://docs.python.org/3/
- NumPy docs: https://numpy.org/doc/
- pandas docs: https://pandas.pydata.org/docs/
- Matplotlib docs: https://matplotlib.org/stable/users/index.html
- Seaborn docs: https://seaborn.pydata.org/
- scikit-learn docs/user guide: https://scikit-learn.org/stable/user_guide.html

### Deep learning frameworks

- PyTorch docs: https://pytorch.org/docs/stable/index.html
- TensorFlow docs: https://www.tensorflow.org/learn
- Keras docs: https://keras.io/

### Jupyter ecosystem

- Jupyter docs: https://docs.jupyter.org/en/latest/
- IPython docs: https://ipython.readthedocs.io/en/stable/

## 5) Repository Conventions

- Keep notebooks grouped by pedagogical intent:
  - `theory/` for conceptual notebooks
  - `exercises/` for hands-on labs
- Keep dependency list in `requirements.txt` aligned with real imports.
- Keep setup instructions in `README.md` synchronized with dependencies.

## 6) Communication Style

- Be concise, clear, and action-oriented.
- Provide short progress updates while working.
- Summarize final output with:
  - changed files,
  - key decisions,
  - commit hash,
  - push status.

## 7) Safety and Integrity

- Do not fabricate sources, metrics, or experimental results.
- Do not invent unsupported claims about model behavior.
- Clearly state limits when data/context is insufficient.
- Respect privacy/security: never expose credentials or secrets.

## 8) Quick Checklist Before Finishing

- [ ] Notebook names are clear and consistent.
- [ ] Notebooks are correctly split into `theory/` and `exercises/`.
- [ ] `README.md` is updated.
- [ ] `requirements.txt` reflects actual dependencies.
- [ ] Explanations use official/academic resources where relevant.
- [ ] Changes are committed (and pushed if remote is available).
