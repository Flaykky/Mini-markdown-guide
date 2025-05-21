# Mini Markdown Guide

Welcome to the Mini Markdown Guide! This concise handbook will teach you the essentials of Markdown, a lightweight markup language for creating formatted text using a plain-text editor.

---

## 1. Headings

Use the hash symbol (`#`) followed by a space to create headings. More hashes mean smaller headings.

```markdown
# H1 - Largest Heading
## H2
### H3
#### H4
##### H5
###### H6 - Smallest Heading
```

---

## 2. Emphasis

* **Bold**: `**bold text**` or `__bold text__`
* *Italic*: `*italic text*` or `_italic text_`
* ***Bold & Italic***: `***text***` or `___text___`
* ~~Strikethrough~~: `~~strikethrough~~`

---

## 3. Lists

### Unordered Lists

Use `-`, `*`, or `+`:

```markdown
- Item 1
- Item 2
  - Subitem 2.1
* Item 3
```

### Ordered Lists

Use numbers followed by a dot:

```markdown
1. First item
2. Second item
   1. Nested item
3. Third item
```

---

## 4. Links and Images

### Links

```markdown
[Link text](https://example.com)
```

### Images

```markdown
![Alt text](https://example.com/image.jpg "Optional title")
```

---

## 5. Code

### Inline Code

Wrap code in backticks: ``Here is `inline code`.``

### Code Blocks

Use triple backticks or indent four spaces:

<pre markdown="1">
```plaintext
def hello():
    print("Hello, Markdown!")
```
</pre>

Optionally specify language after the backticks for syntax highlighting:

```python
print("Hello, Python Markdown!")
```

---

## 6. Blockquotes

Start lines with `>`:

```markdown
> This is a blockquote.
>
> It can span multiple lines.
```

---

## 7. Horizontal Rules

Use three or more hyphens, asterisks, or underscores:

```markdown
---
***
___
```

---

## 8. Tables

Create tables with pipes `|` and hyphens `-`:

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Data     | More     |
| Row 2    | Content  | Values   |
```

---

## 9. Inline HTML

You can include raw HTML for advanced formatting:

```markdown
<details>
<summary>Click to expand</summary>

Hidden content.

</details>
```

---

## 10. Tips & Tricks

* You don’t need to number ordered lists correctly; Markdown will auto-number:

  ```markdown
  1. First
  1. Second
  1. Third
  ```
* Reference-style links for cleaner text:

  ```markdown
  [Example][1]

  [1]: https://example.com "Title"
  ```
* Escaping characters: prefix with backslash `\` to render literal symbols.

---



(Distributed under the MIT License. See [LICENSE](LICENSE) file for details.)




## Conclusion

Congratulations! You now know the core Markdown elements to create well-formatted documents. For more details, explore the [CommonMark Spec](https://commonmark.org/) or your platform’s extended syntax.

Happy writing!
