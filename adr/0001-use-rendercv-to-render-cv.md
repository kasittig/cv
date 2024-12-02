# Render My CV with RenderCV

## Context and Problem Statement

Laying out text is complicated. My CV will change as I gain experience, and I want to use a layout and format that is simple to update.

This ADR answers: what tooling should I use to lay out my CV?

## Considered Options

* Custom LaTeX template
* Use [mikabr's CV format](https://github.com/mikabr/mikabr.github.io/blob/master/files/mikabr-cv/mikabr-cv.Rmd)
* Manually lay out using [Canva](https://www.canva.com/)
* [RenderCV Python library](https://github.com/rendercv/rendercv)
* [RenderCV web app](https://rendercv.com/)
* [Overleaf template](https://www.overleaf.com/latex/templates/tagged/cv)

## Decision Outcome

Chosen option: RenderCV Python library, because

* Manually laying out my CV was a huge pain.
* I find the RenderCV templating format flexible and easy to use.
* I prefer self-hosting my CV over using a webapp.
* I prefer keeping the data in my CV separate from the layout / templating code.
* I like YAML.
* I can easily change the format of my CV in the future if needed.