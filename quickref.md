# Quick reference guide from my teacher

Use this as a "quick reference" guide to writing with Markdown:

## Lists

To write an ordered list (also called "numbered list") write it with numbers:

1. First step
2. Next step
3. Last step

To write an unordered list (also called a "bullet list") write a dash or asterisk
to represent a "bullet":

* Markdown
* HTML
* DITA

Or:

- Windows
- Linux
- MacOS

## Quotes

There's nothing special about inline quotes, just write it with regular quote
marks: "The overriding design goal for Markdown's formatting syntax is to make it
as readable as possible." (Daring Fireball)

To include a longer block quote, format it like a regular paragraph, but add
"greater than" symbols before each line:

> The idea is that a Markdown-formatted document should be publishable
> as-is, as plain text, without looking like it's been marked up with tags
> or formatting instructions. While Markdown's syntax has been influenced
> by several existing text-to-HTML filters, the single biggest source of
> inspiration for Markdown's syntax is the format of plain text email.

## Sample code

Write inline code using backticks, like this example that demonstrates
how to use the `libreoffice` program from the command line to convert a
document to PDF format:

```
$ libreoffice --convert-to pdf report.odt
converting report.odt as a Writer document -> report.pdf using filter : writer_pdf_Export
```

Or, you can write block code samples with four leading spaces:

    $ libreoffice --convert-to pdf report.odt
    converting report.odt as a Writer document -> report.pdf using filter : writer_pdf_Export

## Links and images

Add links to other documents or web pages using brackets and parenthesis.
See the [Markdown Guide](https://www.markdownguide.org/) website for more
examples.

Images use a similar syntax. Note that images are always inline; if you
write an image reference as its own "paragraph," Markdown may or may not
apply special formatting for it:

Web browsers used to show a ![lock icon](/icons/lock.png) lock symbol to
confirm that you were accessing a page using HTTPS.

![screenshot of old Firefox browser with the lock icon](/images/screenshot.png)

## Tables

You can add a table by "drawing" it with vertical and horizontal lines.
The vertical bars do not need to "line up":

| Week | What we'll cover |
| ---- | ---------------- |
| 1    | Docs as Code, GitHub, and Markdown |
| 2    | Technical writing with Markdown    |
