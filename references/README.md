# References

This folder stores the bibliography used by the Quarto website.

## Main file

- `references.bib`: central BibTeX file for all citations in the site.

## How to add a citation

1. Open `references.bib`.
2. Add a new BibTeX entry such as `@article`, `@book`, or `@misc`.
3. Give it a unique citation key, such as `cornelis2019` or `smithMetabolomics2024`.
4. Save the file.

## How to cite in a `.qmd` file

Use the citation key inside your text:

- Narrative style: `@cornelis2019`
- Parenthetical style: `[@cornelis2019]`
- Multiple citations: `[@cornelis2019; @smithMetabolomics2024]`

## How to print the reference list

Add this where you want the bibliography to appear in a page:

```markdown
## References

::: {#refs}
:::
```

Quarto will then render all cited references on that page.
