# en.ergie.at

This contains helpful information related to the [en.ergie.at](https://en.ergie.at) page.

## Writing

- The main language for now is _Deutsch_ (German) --- "DE".
- Make use of footnotes.
- Cite stuff that can be cited, link to stuff that can be linked to.
- Use `<mark>` to highlight stuff, instead of over-using bold/italic text.
- The "readmore" tag `<!--more-->` can be used.

### Highlighting content

```markdown
Dies ist ein wichtiges <mark>Thema</mark>.
```

### Abbreviations

```markdown
<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.
```

These are not supposed to be used for topics that are better cross-referenced, e.g., `DA market` (for day-ahead market) can be used, but should then be used as link `[DA market](/wissen/...)`.

### Sub- and superscripts

```markdown
H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>
```

Make sure to use these accordingly. "CO2", "MWh_el", etc., are examples for their application.

### Rendering math

Include

```markdown
{{< katex >}}
```

in the document to render math stuff. `\\( ... \\)` for inline, `$$ ... $$` for block style.

### `topics`

```markdown
```

### `series`

```markdown
Strommärkte
```

## Templates

### Creating a new author

Assuming a new author named `Jane Doe`:

1. Create `data/authors/jdoe.json`, with the content `{"name": "Jane Doe"}`.
2. Create a short-bio including social links at `content/authors/jdoe/_index.md`.

Template for the bio:

```markdown
---
title: "Jane Doe"
---

[{{< icon "github" >}} j11doe](https://github.com/j11doe) &nbsp;&middot;&nbsp; [{{< icon "linkedin" >}} jane-doe-17](https://at.linkedin.com/in/jane-doe-17)

_Jane's Kurzbiografie hier (Achtung: der Name kommt weiter unten noch einmal vor! Beispiele finden sich hier: https://en.ergie.at/authors/)_

Jane hat an den folgenden Inhalten mitgearbeitet:

```

## Development

### Local setup

1. Install Hugo: [gohugo.io/installation](https://gohugo.io/installation/)
2. Execute `hugo server --buildDrafts`

### Creating a new page

```shell
hugo new content content/path/to/file.md
```

### Commit messages

Read up on [conventionalcommits.org](https://www.conventionalcommits.org/), and stick to the following:

- `chore`: for any general "chores" around the repository
- `hugo`: any changes to the Hugo configuration, theme configuration, or the theme itself
- otherwise tag the main "thing" that you are modifying improving (instead of the usual `fix`, `feat`, etc.)

Regarding the last point, some examples:

- Modifying something in an author's page: `authors: update XY bio`
- Adding some page to the section `wissen`: `wissen: add balancing energy market page`
- Fixing something in the section `daten`: `daten(fix): update interval of ABC`

As you see the "tags" are always aligned with the folder names, "authors", "wissen", etc. Minor changes to language can
be done as `wissen(fix): language`, pure typos as `daten(fix): type`.
