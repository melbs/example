### Third level heading

In Markdown, you want to write everything the same way you might write it in
a plain text docuemnt. think back to the 1980s or 1990s when email was very
new, and you ouldn't do formatting like bold and italics. That's where you started
the convention of stars for **bold** and *italic*.

Think about how you'd write a list in a plain text document.
Numbered lists (*ordered* list) are just lists with a number in front.
So for exmaple
We'll learn later in the DITA unit about three kinds of DITA documents:

1. DITA Concept
1. DITA Task
3. DITA Reference

What about bullet lists? This is an example of an *unorderd* list.
For example, when we learn about DITA, we'll learn about other ways to combine
and modify DITA documents:

* DITA
* DITA Val

You can also use a different character to start an unordered list. Many people
would use a hyphen to make an unordered list in plain text:

- DITA Map
- DITA Val

You can provide block quotes in a Markdown document. Regular quote marks are just
for "inline" quotes. But if you need to quote something longer than about a line, 
then you should use a block quote.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
> incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
> exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure
> dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

### A brief introduction to HTML

The next unit is HTML and we'll learn about *tags* and *elements*.
One example of an HTML tag is `<em>` to provide emphasis.
or `<strong>` for strong emphasis,
or `<p>` for a paragraph. 
For example, we'll learn in the HTML unit that a minimally valid
HTML file might look like this:

```
<!DOCTTYPE html>
<html landg="en">
<head>
  <title>..</title>
</head>
<body>
  ..
</body>
<html></html>
```

You can also add blok code with leading spaces. I don't usually do that,
because the leading spaces can sometimes cause problems or make things
confusing.
One example where leading spaces are confusing is old-style FORTRAN,
which is a programming language that dates to the 1950s and spaces
are significant. 

```
      DO 10 i=1,10,1
      PRINT *,I
10    CONTINUE
```

    is this is a block code
    is this?
    and this one too?
