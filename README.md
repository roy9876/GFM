# GFM
Github Flavored Markdown reference

### TOC
- [External Cheatsheets](#external-cheatsheets)
- [Horizontal Rule](#horizontal-rule)
- [Links](#links)
  - [Inline links](#inline-links)
  - [Reference links](#reference-links)
  - [Heading & Section or Table of Contents Links](#heading--section-table-of-contents-links)
  - [Custom Anchors or links for non-headings](#custom-anchors-or-links-for-non-headings)
- [Headers](#headers)
- [Hide a line](#hide-a-line)
- [Collapsible lines](#collapsible-lines)
- [Display Code as plain text](#display-code-as-plain-text)
- [Show Keyboard style keys or buttons](#show-keyboard-style-keys-or-buttons)
- [Pre-formatted text](#pre-formatted-text)
- [Multi-line text](#multi-line-text)
- [Blockquotes](#blockquotes)

- [Text Formats](#text-formats)
  - [Bold](#bold)
  - [Italic](#italic)
  - [Bold and Italics](#bold-and-italic)
  - [Underlined](#underlined)
  - [Strike-through](#strike-through)
  - [Highlight](#highlight)

- [Emojis](#emojis)
- [Tables](#tables)
- [Unordered Lists](#unordered-list)
- [Ordered Lists](#ordered-list)
- [Alerts](#alerts)

- [Without#goesback2main](back-to-main)
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

### Links
#### [Inline Links](https://github.com/roy9876/GFM/)
Inline Links in the header are done like this using brackets
```
#### [Inline Links](https://github.com/roy9876/GFM/)
```

Or you can use angle brackets to show whole clickable link itself <https://github.com/roy9876/GFM/>
```
Or you can use angle brackets to show whole clickable link itself <https://github.com/roy9876/GFM/>
```

#### Reference Links
Reference Links like this.

```
[Official Github reference][reference text] with examples on section links format using reference text

[Link using reference number][2]

[Markdown-Cheat-Sheet]

[reference text]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links
[2]: https://github.com/lifeparticle/Markdown-Cheatsheet
[Markdown-Cheat-Sheet]: https://github.com/lifeparticle/Markdown-Cheatsheet
```

[Official Github reference][reference text] with examples on section links format using reference text

[Link using reference number][2]

[Markdown-Cheat-Sheet]


[reference text]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links
[2]: https://github.com/lifeparticle/Markdown-Cheatsheet
[Markdown-Cheat-Sheet]: https://github.com/lifeparticle/Markdown-Cheatsheet

(Try to avoid reusing the same number or reference text identifiers for new links otherwise Github might start appending suffixes like #my-header, #my-header-1, #my-header-2, but when you call the reference link if you dont specify the suffix then it will all link the same thing and it just gets confusing)


#### Heading & Section Table of Contents Links

the clickable [Table of Contents](#toc) "Links" sub-section at the top that links within the same page looks like this: 

```
- [Links](#links)
  - [Inline links](#inline-links)
  - [Reference links](#reference-links)
  - [Heading & Section or Table of Contents Links](#heading--section-table-of-contents-links)
```

The displayed text part [in square brackets] can say whatever you want\
Note that for the actual link (in normal semicircle brackets part) you must
  - begin with a hastag (#) if you are referencing a section on the same webpage (otherwise it goes to default main repo and looks for a file with the tag name)
  - remove any UPPER CASE letters and make them LOWER CASE.
  - replace any any <kbd>Space</kbd> (including multiple spaces) with a hyphen (-) 
  - remove any other non-letter characters and punctuation marks such as ?, :, (, or ) but doesnt seem to include the hypthen (-) itself
  - replace some [special characters][reference text] (like '&' in this example) with multiple hyphens (--)

#### Custom Anchors or links for non-headings

If you want to link to a specific paragraph, a list item, or an image without turning it into a header, you can insert a manual HTML <a> tag or an id attribute. GitHub Flavored Markdown will parse these and allow you to jump straight to them

**_Using an anchor tag:_**
```
<a id="custom-paragraph-target"></a> This is a regular paragraph that isn't a header.

[Jump to the regular paragraph](#custom-paragraph-target)
```
<a id="custom-paragraph-target"></a> This is a regular paragraph that isn't a header.

[Jump to the regular paragraph](#custom-paragraph-target)


These are anchor links to the second & third items from the unordered list section below (code replicated here to show the "a id" tag placement) that isn't a header.
```
<ul>
<li>First item</li>
<li><a id="custom-ul-target2"></a>Second item (un-indicated anchor link)</li>
<li><a id="custom-ul-target3">Third item (indicated or underlined anchor link)</a></li>
<li>Fourth item</li>
</ul>
```
[Jump to the second item of the unordered list below](#custom-ul-target2)\
[Jump to the third item of the unordered list below](#custom-ul-target3)


**_Using an ID on standard text blocks:_**
```
<p id="my-unique-id">This is text inside an HTML paragraph tag.</p>

[Jump to the HTML paragraph](#my-unique-id)
```
<p id="my-unique-id">This is text inside an HTML paragraph tag.</p>

[Jump to the HTML paragraph](#my-unique-id)

<br>

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

An alternative Link Reference Hack to hide a line entirely is by formatting it as an unused Markdown link reference.
```
[//]: # (This line is also hidden on Github)
```

[//]: # (This line is also hidden on Github)


### Collapsible lines
```
<details>
  <summary>Click here to expand and view the hidden line(s)</summary>
  These are the hidden lines that will expand.

  when you click
</details>
```
<details>
  <summary>Click here to expand and view the hidden line(s)</summary>
  These are the hidden lines that will expand.

  when you click
</details>


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


### Show Keyboard style keys or buttons

```
<kbd>Space</kbd>
```
for <kbd>Space</kbd>

or `<kbd>Write anything</kbd> + <kbd>you want</kbd> including <kbd>[button links](https://github.com/lifeparticle/Markdown-Cheatsheet/blob/main/README.md#buttons)</kbd>` 

for <kbd>Write anything</kbd> + <kbd>you want</kbd> including <kbd>[button links](https://github.com/lifeparticle/Markdown-Cheatsheet/blob/main/README.md#buttons)</kbd>

### <pre>Pre-formatted      text</pre>
```
<pre>Pre-formatted      text </pre>
```
### Multi-line text
```
Use the\
backslash\
display multi-line preformatted text\
like this.
```
Use the\
backslash\
display multi-line preformatted text\
like this.



### Blockquotes
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

#### <strong>Bold</strong>
For Keyboard shortcut just Press <kbd>Ctrl</kbd> + <kbd>B</kbd> (or <kbd>Cmd+B</kbd> in Mac)
```
**Bold**
__Bold__
<strong>Bold</strong>
```

#### <em>Italic.</em>
For Keyboard shortcut just Press <kbd>Ctrl</kbd> plus <kbd>i</kbd> (or <kbd>Cmd+I</kbd> in Mac)
```
*Italic.*
_Italic._
<em>Italic.</em>
```

#### <strong><em>Bold AND Italic</em></strong>
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

#### ==Highlight.==
```
==Highlight==
```
==Highlight==

### Emojis :cool:
```
:smiley:
```
:smiley:

### Tables
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


### Unordered List
```
<ul>
<li>First item</li>
<li><a id="custom-ul-target2"></a>Second item (un-indicated anchor link)</li>
<li><a id="custom-ul-target3">Third item (indicated or underlined anchor link)</a></li>
<li>Fourth item</li>
</ul>
```
<ul>
<li>First item</li>
<li><a id="custom-ul-target2"></a>Second item (un-indicated anchor link)</li>
<li><a id="custom-ul-target3">Third item (indicated or underlined anchor link)</a></li>
<li>Fourth item</li>
</ul>


```
- First level (bullet point)
  - Second level
    - Third level
      - Fourth level
+ First level (still bullet point)
  + Second level
* First level (still bullet point)
  * Second level
 ```

- First level (bullet point)
  - Second level
    - Third level
      - Fourth level
+ First level (still bullet point)
  + Second level
* First level (still bullet point)
  * Second level


For Keyboard shortcut Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>8</kbd> (or <kbd>Cmd+Shift+8</kbd> in Mac)



### Ordered List
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

For Keyboard shortcut Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>7</kbd> (or <kbd>Cmd+Shift+7</kbd> in Mac)

### Alerts

> [!NOTE]
> NOTES are blue. Essential details that users should not overlook, even when browsing quickly.

<br>

> [!TIP]
> TIPS are green. Additional advice to aid users in achieving better outcomes.

<br>

> [!IMPORTANT]
> IMPORTANT are purple. Vital information required for users to attain success.

<br>

> [!WARNING]
> WARNINGS are yellow. Urgent content that requires immediate user focus due to possible risks.

<br>

> [!CAUTION]
> CAUTION are red. Possible negative outcomes resulting from an action.




