Title: PPM Extras
Date: 05-05-2025
Author: Cedar DeLacy

This is an additional document that goes with the [People's Power Movement essay.](People's%20Power%20Movement.html)
## Justification for formatting
### Overview
I prefer to use a text format called [Markdown](https://en.wikipedia.org/wiki/Markdown), it allows me to write without distraction while retaining the use of many formatting tools. Markdown is a documentation standard that is focused mainly on text rendering, files are denoted by the use of the markdown file format (.md or .markdown). Although possessing a different file extension, markdown files are fully backwards compatible with plain text (.txt), formatting is provided by special characters interpreted by the markdown renderer (a table of common formatting is provided below for interpreting markdown viewed in a text editor lacking support).

> "The overriding design goal for Markdown's formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions." --- John Gerber, the original creator of markdown. [^1]

I personally use [Obsidian](https://obsidian.md) to write markdown as it has great extension support through plugins along with a very easy to use text editor.
Markdown does have some downsides however, to retain full backwards compatibility with plain text, some sacrifices have to be made compared to a format such as docx. While the [commonmark spec (ver. 0.31.2)](https://spec.commonmark.org/0.31.2/) supports the use of inline CSS and HTML to style text, I prefer not to use it as it make reading markdown in an incompatible viewer more difficult. This choice limits me in terms of rich formatting, but I think that it contributes to visual cohesion and clarity.

### Header

I'm not using a header or footer in this document, as support doesn't exist in Markdown. This means that my raw files lack page numbers, something that's common in Markdown as it's a pageless format. Title and author information is provided at the top of the document.

### Quotes

I'm using markdown quote-blocks because they offer visual separation from the rest of the text. Quote-blocks are denoted by a greater-than sign (`>`) at the beginning of a line. Sources for quotes are provided as a foot note, this is done to retain flow in the writing while still properly attributing information. Footnotes are denoted by a superscript numeral inside brackets (eg: \[\^1\] ), the corresponding text can be found at the bottom of the document.

### Sources and inter-document links

The markdown spec allows documents to link to other documents, most editors support this, but some don't. Markdown documents converted to other formats such as pdf and docx may or may not support this behavior, this largely depends on the abilities of the format and the features the conversion tool supports.
This document is linked from the main essay and backlinks to it, if you're working in an environment that doesn't support file linking, look for format characters that symbolize a link.
Links between files are denoted by two sets of brackets surrounding the name of the file they're linking to without a file extension; \[\[People's Power Movement\]\]
External links have two parts, the link text and the link destination. The link text is surrounded by a single set of brackets: \[this text is a link\].
The link destination is a url within parentheses immediately following the link text: `(https://example.com)`.
A full link would look like this: `[this text is a link](https://example.com)`.

### Common markdown format characters

| Character purpose | Character      | Character placement |
|-------------------|----------------|---------------------|
| Heading 1 / Title | \#             | Before a line       |
| Heading 2... 6    | \##... \###### | Before a line       |
| Quote block       | \>             | Before a line       |
| Italics           | \_ or \*       | Surrounding text    |
| Bold              | \*\*           | Surrounding text    |
| Unordered list    | \-             | Before a line       |
| Ordered list      | 1\.            | Before a line       |
| Strikethrough     | \~\~           | Surrounding text    |

[^1]: Gerber, John. "Markdown", DaringFireball, 17 Dec 2004, [https://daringfireball.net/projects/markdown/](https://daringfireball.net/projects/markdown/).
