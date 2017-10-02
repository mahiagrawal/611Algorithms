A few notes from HW1:
- There's rarely a need to use `\newline` or its equivalent, `\\`. Usually it's fine to just leave an empty line in between paragraphs.
- `$x < y$` is better than `$x$ \textless $y$` because it doesn't mess up the spacing. In general, most symbols should be inside math mode. If you find yourself using `\text[something]` outside math mode, there's probably a better way to do it.
- Remember to always put variables in math mode, wherever they appear. Even single numbers should usually be in math mode, e.g. `There are $4$ possible cases.`
- I added a pseudocode package (algpseudocode) to the template. HW1 Q4 has an example of how to use it.

Remember to put each sentence on a new line; LaTeX won't care, but github will give us fewer merge conflicts.

Some useful links for getting help with LaTeX:

- Great wiki with pretty much every command you'll ever need to know: https://en.wikibooks.org/wiki/LaTeX
- If you don't know the command for a symbol, you can draw it in here: http://detexify.kirelabs.org/classify.html
- Also, most editors have a LaTeX package that provides some good IDE features.
