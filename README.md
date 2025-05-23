# Mini Markdown Guide

Welcome to the Mini Markdown Guide! This handbook introduces you to Markdown, a simple and lightweight markup language that lets you create formatted text using a plain-text editor. Whether you’re writing blog posts, documentation, or notes, Markdown makes formatting easy and fun. Let’s dive in!

---

## Table of Contents

1. [Headings](#1-headings)  
2. [Emphasis](#2-emphasis)  
3. [Lists](#3-lists)  
4. [Links and Images](#4-links-and-images)  
5. [Code](#5-code)  
6. [Blockquotes](#6-blockquotes)  
7. [Horizontal Rules](#7-horizontal-rules)  
8. [Tables](#8-tables)  
9. [Inline HTML](#9-inline-html)  
10. [Tips & Tricks](#10-tips--tricks)  
11. [Conclusion](#11-conclusion)  

---

## 1. Headings

Headings organize your content into sections. Use the hash symbol (`#`) followed by a space to create them. The number of hashes sets the heading level, from `#` (largest) to `######` (smallest).

```markdown
# H1 - Main Title
## H2 - Section
### H3 - Subsection
#### H4
##### H5
###### H6 - Tiny Heading
```

**Example Output:**  
# H1 - Main Title  
## H2 - Section  
### H3 - Subsection  

**Tip:** Use H1 for your document’s title and H2-H6 for structuring sections and subtopics.

---

## 2. Emphasis

Make your text stand out with emphasis:  

- **Bold**: Wrap text in double asterisks `**bold**` or underscores `__bold__`.  
- *Italic*: Use single asterisks `*italic*` or underscores `_italic_`.  
- ***Bold & Italic***: Combine with triple asterisks `***bold italic***` or underscores `___bold italic___`.  
- ~~Strikethrough~~: Use double tildes `~~strikethrough~~`.  

```markdown
This has **bold**, *italic*, ***bold italic***, and ~~strikethrough~~ text.
```

**Example Output:**  
This has **bold**, *italic*, ***bold italic***, and ~~strikethrough~~ text.

**Tip:** Use emphasis sparingly to highlight key points without overwhelming the reader.

---

## 3. Lists

Lists help you present information clearly. Markdown supports unordered and ordered lists.

### Unordered Lists

Start items with `-`, `*`, or `+` followed by a space:  

```markdown
- Apple
- Banana
  - Yellow
  - Sweet
* Orange
+ Grape
```

**Example Output:**  
- Apple  
- Banana  
  - Yellow  
  - Sweet  
* Orange  
+ Grape  

**Tip:** Nest items by indenting with two spaces.

### Ordered Lists

Use numbers followed by a dot and a space:  

```markdown
1. Step one
2. Step two
   1. Substep 2.1
   2. Substep 2.2
3. Step three
```

**Example Output:**  
1. Step one  
2. Step two  
   1. Substep 2.1  
   2. Substep 2.2  
3. Step three  

**Note:** Numbers don’t need to be sequential; Markdown auto-corrects them.

---

## 4. Links and Images

### Links

Add clickable links with this format: `[text](URL "optional title")`.  

```markdown
[Google](https://google.com "Search Engine")
```

**Example Output:**  
[Google](https://google.com "Search Engine")  

### Images

Embed images using an exclamation mark `!`, alt text, and a URL:  

```markdown
![Cute Cat](https://example.com/cat.jpg "A fluffy kitten")
```

**Tip:** Alt text improves accessibility by describing the image if it doesn’t load.

---

## 5. Code

Show off code snippets with proper formatting.

### Inline Code

Wrap short code in single backticks:  

```markdown
Use `print("Hello")` to display text.
```

**Example Output:**  
Use `print("Hello")` to display text.

### Code Blocks

For larger code, use triple backticks (```) or indent with four spaces. Add a language name for syntax highlighting:  

```markdown
```python
def greet():
    print("Hello, Markdown!")
```
```

**Example Output:**  
```python
def greet():
    print("Hello, Markdown!")
```

**Tip:** Common languages include `python`, `javascript`, `html`, and `css`.

---

## 6. Blockquotes

Quote text or add notes with a `>` at the start of each line:  

```markdown
> Markdown is awesome!
>
> It’s simple and versatile.
```

**Example Output:**  
> Markdown is awesome!  
>  
> It’s simple and versatile.  

**Tip:** Use blockquotes for quotes, asides, or to emphasize important notes.

---

## 7. Horizontal Rules

Separate sections with a horizontal line using three or more `-`, `*`, or `_`:  

```markdown
---
```

**Example Output:**  
---

**Tip:** Great for breaking up long documents into readable chunks.

---

## 8. Tables

Organize data with tables using pipes `|` and hyphens `-`:  

```markdown
| Name     | Age | City    |
|----------|-----|---------|
| Alice    | 25  | London  |
| Bob      | 30  | New York|
```

**Example Output:**  
| Name     | Age | City    |  
|----------|-----|---------|  
| Alice    | 25  | London  |  
| Bob      | 30  | New York|  

**Tip:** Add colons to align text: `|:---|` (left), `|---:|` (right), `|:---:|` (center).

---

## 9. Inline HTML

For extra formatting, use raw HTML directly in your Markdown:  

```markdown
<details>
<summary>Click me!</summary>
Surprise! Hidden text here.
</details>
```

**Example Output:**  
<details>  
<summary>Click me!</summary>  
Surprise! Hidden text here.  
</details>  

**Note:** Keep HTML minimal to preserve Markdown’s simplicity.

---

## 10. Tips & Tricks

Level up your Markdown with these handy tips:  

- **Auto-numbered Lists:** Markdown fixes numbering for you:  
  ```markdown
  1. One
  1. Two
  1. Three
  ```  
  Becomes:  
  1. One  
  2. Two  
  3. Three  

- **Reference-style Links:** Cleaner links with references:  
  ```markdown
  [GitHub][1] is great!  
  [1]: https://github.com "Code Hosting"
  ```

- **Escaping Characters:** Use `\` to show special characters literally:  
  ```markdown
  \*Not italic\* and \#Not a heading\#
  ```  
  Output:  
  *Not italic* and #Not a heading#  

- **Line Breaks:** Add two spaces at the end of a line for a new line without a new paragraph.  

- **Task Lists:** Some platforms support checkboxes:  
  ```markdown
  - [x] Done
  - [ ] To do
  ```

- **Emojis:** Add flair with `:emoji-name:` (e.g., `:smile:` = 😊) on supported platforms.

---

## 11. Conclusion

Well done! You’ve mastered the essentials of Markdown. With these tools, you can create polished, structured documents effortlessly. Practice a little, and soon you’ll be a Markdown pro! For more features, check the [CommonMark Spec](https://commonmark.org/) or your platform’s documentation.

Happy writing!

---

*(Distributed under the MIT License. See [LICENSE](LICENSE) file for details.)*

---
