# Jupyter Notebook Markdown Guide

## Introduction
This guide provides a complete reference for using Markdown in Jupyter Notebook, including headers, text formatting, lists, code blocks, tables, links, images, and more.

---

## 1. Switching to Markdown Mode
To write in Markdown, change the cell type to Markdown.
- **Shortcut:** `Esc + M`

---

## 2. Headers (Headings)
Use `#` for different levels of headers.
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

---

## 3. Text Formatting
### Bold Text
```markdown
**This is bold**
__This is also bold__
```

### Italic Text
```markdown
*This is italic*
_This is also italic_
```

### Bold and Italic
```markdown
***This is bold and italic***
___This is also bold and italic___
```

### Strikethrough Text
```markdown
~~This is strikethrough~~
```

---

## 4. Lists
### Unordered List
```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
```

### Ordered List
```markdown
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
```

### Mixed List
```markdown
1. First item
   - Subitem A
   - Subitem B
2. Second item
```

---

## 5. Code Blocks
### Inline Code
```markdown
`print("Hello, World!")`
```

### Multi-line Code Block
```markdown
```python
print("Hello, World!")
```
```

### Syntax Highlighting
```markdown
```javascript
console.log("Hello, World!");
```
```

---

## 6. Links and Images
### Hyperlink
```markdown
[Google](https://www.google.com)
```

### Open Link in New Tab
```markdown
[Google](https://www.google.com){:target="_blank"}
```

### Insert Image
```markdown
![Alt Text](https://example.com/image.jpg)
```

### Resize Image
```markdown
<img src="https://example.com/image.jpg" width="400" height="300">
```

---

## 7. Tables
```markdown
| Name  | Age | Profession |
|-------|-----|-----------|
| John  | 25  | Developer |
| Jane  | 30  | Designer  |
```

---

## 8. Blockquotes
```markdown
> This is a blockquote.
>> This is a nested blockquote.
```

---

## 9. Horizontal Line (Divider)
```markdown
---
```

---

## 10. Task List (Checkboxes)
```markdown
- [x] Task 1 (Completed)
- [ ] Task 2 (Incomplete)
- [ ] Task 3 (Incomplete)
```

---

## 11. Mathematical Expressions (LaTeX Support)
Jupyter Notebook supports LaTeX for writing mathematical expressions.

### Inline Math
```markdown
This is an inline equation: $E = mc^2$
```

### Block Math
```markdown
$$
E = mc^2
$$
```

---

## 12. Emojis
You can add emojis using Markdown syntax.
```markdown
:smile: :rocket: :tada:
```

---

