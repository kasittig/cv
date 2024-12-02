# Use UV for Python Package / Project Management

## Context and Problem Statement

I selected [RenderCV](https://docs.rendercv.com/) to lay out and render my CV. RenderCV is a Python package, and managing dependencies in Python can get hairy without a package manager.

This ADR answers: which package manager should this project use to manage its Python dependencies?

## Considered Options

* [uv](https://docs.astral.sh/uv/)
* [rye](https://rye.astral.sh/)
* [poetry](https://python-poetry.org/)
* [pipx](https://github.com/pypa/pipx)
* YOLO

## Decision Outcome

Chosen option: uv, because

* pipx is not a dependency manager.
* I find that installing Python packages directly onto my machine makes it too difficult to maintain multiple projects.
* rye recommends using uv.
* This project will not be published as a Python package, so I don't need Poetry's support for multiple dependency groups.
* uv replaces both pipx and pyenv which streamlines my development process.