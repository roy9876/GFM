# GFM
Github Flavored Markdown reference

- [External Cheatsheets](#external-cheatsheets)
- [Horizontal Rule](#horizontal-rule)
- [Headers](#headers)
- [Hide a line](#hide-a-line)
- [Display Code as plain text](#display-code-as-plain-text)
- [Show Keyboard style keys](#show-keyboard-style-keys)
- [Pre-formatted text](#pre-formatted--text)
- [Blockquotes](#blockquotes)

- [Text Formats](#text-formats)
  - [Normal](#normal)
  - [Bold](#bold)
  - [Italic](#italic)
  - [Bold and Italic](#bold-and-italic)
  - [Underlined](#underlined)
  - [Strike-through](#strike-through)

- [Tables](#tables)
- [Emojis](#emojis-)
- [Unordered Lists](#unordered-list)
- [Ordered Lists](#ordered-list)

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

[Github-rxaviers-emojis](https://gist.github.com/rxaviers/7360908 "markdown emojis")
https://gist.github.com/rxaviers/7360908

https://towardsdatascience.com/python-done-the-r-markdown-way-d03bec4b96b/

convert excel to markdown
https://tableconvert.com/



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

#### <strong> Bold </strong>
For Keyboard shortcut just Press <kbd>Ctrl</kbd> + <kbd>B</kbd> (or <kbd>Cmd+B</kbd> in Mac) or
```
**Bold**
__Bold__
<strong>Bold</strong>
```

#### <em>Italic.</em>
For Keyboard shortcut just Press <kbd>Ctrl</kbd> plus <kbd>i</kbd> (or <kbd>Cmd+I</kbd> in Mac) or
```
*Italic.*
_Italic._
<em>Italic.</em>
```

#### <strong><em> Bold AND Italic</em></strong>
```
**_Bold AND Italic_**
***Bold AND Italic***
<strong><em>Bold AND Italic</em></strong>
```

#### <ins>Underlined</ins>
```
<ins>Underlined</ins>
```

#### ~~Strike-through.~~
```
~~Strike-through.~~
```


#### Emojis :cool:
```
:smiley:
```
:smiley:

#### Tables
```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

```
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


#### Unordered List
```
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>
```
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>


```
- First level
  - Second level
    - Third level
      - Fourth level
+ First level
  + Second level
* First level
  * Second level
 ```

- First level
  - Second level
    - Third level
      - Fourth level
+ First level
  + Second level
* First level
  * Second level


For Keyboard shortcut Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>8</kbd> (or <kbd>Cmd+Shift+8</kbd> in Mac) or



#### Ordered List
Each ordered level is 2 tabs (2x2=4 spaces) away

```
1. One
2. Two
3. Three
```
1. One
2. Two
3. Three

```
1. First ordered level
    1. Second ordered level
        - Third unordered level
            - Fourth unordered level
2. First ordered level
    1. Second ordered level 1
    2. Second ordered level 2
3. First ordered level
    - Second unordered level
        1. Third ordered level 1
        2. Third ordered level 2
        3. Third ordered level 3
            1. Fourth ordered level      
```
1. First ordered level
    1. Second ordered level
        - Third unordered level
            - Fourth unordered level
2. First ordered level
    1. Second ordered level 1
    2. Second ordered level 2
3. First ordered level
    - Second unordered level
        1. Third ordered level 1
        2. Third ordered level 2
        3. Third ordered level 3
            1. Fourth ordered level   

For Keyboard shortcut Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>7</kbd> (or <kbd>Cmd+Shift+7</kbd> in Mac) or



