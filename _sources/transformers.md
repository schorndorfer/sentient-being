---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Transformers


## An example cell

With MyST Markdown, you can define code cells with a directive like so:

```{code-cell}
print(2 + 2)
```

Here is a [reference to the intro](intro.md). Here is a reference to [](section-label).

(section-label)=
## Reading List

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: ``{cite}`noauthor_mathematics_nodate-1` `` will render like
this: {cite}`noauthor_mathematics_nodate-1`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```
