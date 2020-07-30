---
title: markdown sandbox post
date: 2020-07-31
metavar: this var is defined in metadata
---

this is a sandbox markdown file i use to check the rendering in various app i use (VSCode, Obsidian, iA Writer, Marked 2, Ulysses, Zettlr) which have each custom capabilities

## Table of Contents

{{TOC}}

## Heading IDs {#custom-id}

## blockquotes
Regular text.

> Blockquote
> with two lines.
And one more line.
>> And a second level blockquote.

## custom vars
`metavar` is a variable defined in the yaml metadata: [%metavar]

## maths
molecule: C~6~H~12~O~6~  
exponentials: x^2,y^  
normal<sup>sup</sup>

## Strikethrough
i can strike by ~~striked~~  
or by `<del>` : <del>deleted</del>?


## Syntax Highlighting
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## tables
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

rich ones:

| testa | croce |
|--:|--:|
| inside a cell| a sentence<br>with br  |

## custom font size

can you really render <font size=10>big text?</font>

## Footnotes
Here's a simple footnote,[^1] and here's a longer one.[^bignote]
[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

## citations
Cite a source.[p. 42][#source]

[#source]: John Doe. *A Totally Fake Book*. Vanity Press, 2006.


## emojis
db: <https://emojipedia.org/>
this is a joy emojy! ::joy::
this is an italian flag (copy pasted) 🇮🇹

## tasks
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## definition list
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Automatic URL Linking
http://www.example.com
<http://www.example.com>
[http://www.example.com]()
`http://www.example.com`

## back to top
go to top? [Heading IDs](#custom-id)
