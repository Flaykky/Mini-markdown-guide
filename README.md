
# 📝 MINI Markdown Guide  
**Master Markdown for clean, professional, and accessible documentation.**

---

## 🧭 Table of Contents
1. [Basics](#1-basics)  
2. [Formatting](#2-formatting)  
3. [Advanced Features](#3-advanced-features)  
4. [Best Practices](#4-best-practices)  
5. [Tools & Tips](#5-tools--tips)  

---

## 1. Basics  
### Headings  
Use `#` to `######` for hierarchical headings (H1–H6).  

```markdown
# Main Title (H1)  
## Section (H2)  
### Subsection (H3)  
```

**Output:**  
# Main Title  
## Section  
### Subsection  

**Tip:** Use only **one H1** per document (e.g., for titles).

---

### Emphasis  
Style text with bold, italic, or strikethrough:  

```markdown
**Bold** (`**bold**`)  
*Italic* (`*italic*`)  
~~Strikethrough~~ (`~~strikethrough~~`)
```

**Output:**  
**Bold**  
*Italic*  
~~Strikethrough~~  

**Pro Tip:** Combine styles: `***Bold + Italic***`.

---

### Lists  
#### Unordered Lists  
```markdown
- Item 1  
- Item 2  
  - Nested item  
```

#### Ordered Lists  
```markdown
1. First step  
2. Second step  
   1. Substep  
```

**Output:**  
- Item 1  
- Item 2  
  - Nested item  

**Tip:** Use `-`, `*`, or `+` interchangeably for bullets.

---

## 2. Formatting  
### Links & Images  
```markdown
[Text](https://example.com "Optional title")  
![Alt text](/path/to/image.jpg "Optional hover title")
```

**Example:**  
[GitHub](https://github.com "Code Hosting")  
![Logo](https://example.com/logo.png "Company Logo")  

**Accessibility Note:** Always write descriptive alt text (e.g., `![Graph showing sales growth]` vs. `![Image]`).

---

### Code Snippets  
- **Inline code:** Wrap in backticks:  
  ```markdown
  Use `print("Hello")` in Python.
  ```
- **Code blocks:** Use triple backticks with a language specifier:  
  ```markdown
  ```python
  def hello():
      print("Hello, world!")
  ```
  ```

**Output:**  
```python
def hello():
    print("Hello, world!")
```

---

### Blockquotes  
Quote text with `>`:  
```markdown
> "Markdown is a lightweight markup language."  
> – John Gruber
```

**Output:**  
> "Markdown is a lightweight markup language."  
> – John Gruber  

---

## 3. Advanced Features  
### Tables  
Align columns with colons `:`:  
```markdown
| Name | Age | Role        |  
|:-----|----:|:-----------:|  
| Alice| 28  | Developer   |  
```

**Output:**  
| Name | Age | Role        |  
|:-----|----:|:-----------:|  
| Alice| 28  | Developer   |  

---

### Horizontal Rules  
Separate sections with `---`, `***`, or `___`:  
```markdown
---  
```

---

### Inline HTML  
Embed HTML for advanced elements:  
```markdown
<details>
  <summary>Click to expand</summary>
  Hidden content here!
</details>
```

**Output:**  
<details>  
  <summary>Click to expand</summary>  
  Hidden content here!  
</details>  

---

## 4. Best Practices  
### 📑 Writing Documentation  
- **Use a TOC** for long documents with `[Section](#section-name)`.  
- **Structure hierarchically**: H1 → H2 → H3.  
- **Format code consistently**: Use fenced code blocks with language tags.  
- **Add notes/warnings**:  
  ```markdown
  > ⚠️ **Warning:** Always back up your data.
  ```

### ✅ Accessibility Tips  
- Avoid "click here" links; use descriptive text (e.g., `[GitHub docs](https://github.com/docs)`).  
- Use header levels logically (don’t skip from H1 to H3).  

---

## 5. Tools & Tips  
### 🔧 Popular Markdown Editors  
- **VS Code** (with Markdown extensions)  
- **Typora** (WYSIWYG editor)  
- **Obsidian** (for note-taking)  

### 🚀 Pro Tips  
- **Escape characters**: Use `\` to disable formatting:  
  ```markdown
  \*Literal asterisk\*
  ```
- **Task lists**:  
  ```markdown
  - [x] Complete guide  
  - [ ] Publish online  
  ```
- **Line breaks**: Add two spaces at the end of a line for a soft break.  

---

## 📌 Cheat Sheet  
| Feature       | Syntax               |  
|---------------|----------------------|  
| Bold          | `**text**`           |  
| Italic        | `_text_`             |  
| Link          | `[text](url)`        |  
| Image         | `![alt](url)`        |  
| Code Block    | ```\`\`\`python...```|  

---

**License**: [MIT](LICENSE)  
**Original Source**: [CommonMark Spec](https://commonmark.org/)  

---
