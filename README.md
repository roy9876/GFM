# GFM
Github Flavored Markdown reference

- [External Cheatsheets]{external-cheatsheets}
- [Horizontal Rule](horizontal-rule)
- [Headers]{#headers}
- [Hide a line](#hide-a-line)
- [Display Code as plain text]{display-code-as-plain-text}
- [Show Keyboard style keys]{show-keyboard-style-keys}
- [Pre-formatted text]{pre-formatted--text}
- [Blockquotes]{blockquotes}

- [Text Formats](text-formats)
  - [Normal](normal)
  - [Bold](bold)
  - [Italic](italic)
  - [Bold and Italic](bold-and-italic)
  - [Underlined](underlined)
  - [Strike-through](strike-through)
  - [Blockquotes](blockquotes)
  - [Monospaced](monospaced)

***

### External Cheatsheets


The [Official Github text link]
https://github.github.com/gfm/

[Official Github text link]: https://github.github.com/gfm/

[Github Docs using numbered reference style link definition][1]
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

[1]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

[Github Keyboard Shortcuts](https://docs.github.com/en/get-started/accessibility/keyboard-shortcuts "Github official kb shortcuts")
https://docs.github.com/en/get-started/accessibility/keyboard-shortcuts

[Github-lifeparticle](https://github.com/lifeparticle/Markdown-Cheatsheet)
https://github.com/lifeparticle/Markdown-Cheatsheet

[Github-lifeparticle-textcolours](https://github.com/lifeparticle/Markdown-Cheatsheet/blob/main/MathJax.md "markdown text colours")
https://github.com/lifeparticle/Markdown-Cheatsheet/blob/main/MathJax.md

[GeeksforGeeks](https://www.geeksforgeeks.org/git/markdown-cheat-sheet-github/)
https://www.geeksforgeeks.org/git/markdown-cheat-sheet-github/

[Github-roshith-balendran](https://gist.github.com/roshith-balendran/d50b32f8f7d900c34a7dc00766bcfb9c)
https://gist.github.com/roshith-balendran/d50b32f8f7d900c34a7dc00766bcfb9c

[Github-stevenyap](https://gist.github.com/stevenyap/7038119)
https://gist.github.com/stevenyap/7038119

[Github-adam-p](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet)
https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet

https://towardsdatascience.com/python-done-the-r-markdown-way-d03bec4b96b/


### <ins>Common Used Markdowns</ins>

### Horizontal Rule
---
```
---
***
___
```

### Headers
# Heading 1
`# Heading 1`
```
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
```
\#\#\#\#\#\# Heading 6
###### Heading 6

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```


### Hide a line
<!-- This entire line will be completely hidden from the rendered view -->
```
<!-- This entire line will be completely hidden from the rendered view -->
```


### Display Code as plain text

<ins>Method 1:</ins> Use a Code Block (Best). 
Surround your text with three backticks (3x ` no spaces) on the lines directly above and below the code to show raw code snipped with copy button
\```

```
`` `
### Heading 3
#### Heading 4
`` `
```

<ins>Method 2:</ins> Use Backslashes to Escape.
If you want the text to display inline without a code block box, place a backslash (\) right before your markdown code to ignore
```
\#\#\# Heading 3
\#\#\#\# Heading 4
```
will be like this
\#\#\# Heading 3
\#\#\#\# Heading 4

<ins>Method 3:</ins> Use Inline Code Backticks.
If you want to display each markdown code line on its own line as individual code snippets, wrap each line in single backticks (`)
```
`### Heading 3`
`#### Heading 4`
```
will be like this
`### Heading 3`
`#### Heading 4`

<ins>Method 4:</ins> Use keyboard shortcut (2 backticks)
Press <kbd>Ctrl</kbd> + <kbd>E</kbd> (or <kbd>Cmd+E</kbd> in Mac) which basically inserts 2 backticks

``### Heading 3 (once in the front only)

``#### Heading 4`` (twice, in the front and at the back)


#### Show Keyboard style keys

```
<kbd>Space</kbd>
```
for <kbd>Space</kbd>

or `<kbd>Write anything</kbd> + <kbd>you want</kbd>` for <kbd>Write anything</kbd> + <kbd>you want</kbd>

#### <pre>Pre-formatted      text</pre>
```
<pre>Pre-formatted      text </pre>
```


#### Blockquotes
```
> Simple Blockquote
```
> Simple Blockquote

```
> These are multiple
>
> lines of 
>
> blockquotes.
```
> These are multiple
>
> lines of 
>
> blockquotes.

```
> 1st level (Regular) blockquote
>> 2nd level blockquotes.
>>> 3rd level blockquotes
>>>> 4th level blockquotes with ``### Header 3`` code
```
> 1st level (Regular) blockquote
>> 2nd level blockquotes.
>>> 3rd level blockquotes
>>>> 4th level blockquotes with ``### Header 3`` code

```
> **Bold** <strong><em>and</em></strong> *Italic* blockquotes
```
> **Bold** <strong><em>and</em></strong> *Italic* blockquotes



### Text Formats

#### <strong> Bold. </strong>
For Keyboard shortcut just Press <kbd>Ctrl</kbd> + <kbd>B</kbd> (or <kbd>Cmd+B</kbd> in Mac) or
```
**Bold.**
__Bold.__
<strong>Bold.</strong>
```

#### <em>Italic</em>
For Keyboard shortcut just Press <kbd>Ctrl</kbd> plus <kbd>i</kbd> (or <kbd>Cmd+I</kbd> in Mac) or
```
*Italic*
_Italic_
<em>Italic</em>
```

#### <strong><em> Bold AND Italic.</em></strong>
```
**_Bold AND Italic._**
***Bold AND Italic.***
<strong><em>Bold AND Italic.</em></strong>
```

#### <ins>Underlined</ins>
```
<ins>Underlined</ins>
```

#### ~~Strike-through.~~
```
~~Strike-through.~~
```



