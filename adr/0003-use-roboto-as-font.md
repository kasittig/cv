# Use Roboto as CV font

## Context and Problem Statement

I need to pick a font for my CV that reflects my personal style.

## Considered Options

* [Roboto](https://fonts.google.com/specimen/Roboto)
* An included rendercv font

## Decision Outcome

Chosen option: "Roboto" because Roboto is my preferred personal font and I like using it everywhere.

### Consequences

* Good, because my CV's font now reflects my personal style.
* Bad, because I can no longer compile my CV using rendercv's LaTeX installation and now must compile my CV locally.

Command: `uv run rendercv render --use-local-latex-command pdflatex Karen_Sittig_CV.yaml`
