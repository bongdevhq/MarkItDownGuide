# MarkItDownGuide
## A comprehensive guide to mastering Markdown. Open to contributions and updates. Contribute, learn, and share. Let's make documentation beautiful together!

## Markdown Language Tutorial

### 1. Headings

**Markdown Code:**

```
'# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 '
```

**Output:**

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### 2. Bold

**Markdown Code:**

```
`**Bold Text**'
```

**Output:** **Bold Text**

### 3. Italic

**Markdown Code:**

```

`*Italic Text*` 
```
**Output:** _Italic Text_

### 4. Bold and Italic

**Markdown Code:**

```

`***Bold and Italic Text***` 
```
**Output:** _**Bold and Italic Text**_

### 5. Strikethrough Text

**Markdown Code:**

```

`~~Strikethrough Text~~` 
```
**Output:** ~~Strikethrough Text~~

### 6. Unordered List of Items

**Markdown Code:**

```

`- Item 1
- Item 2
 - Subitem 2.1
 - Subitem 2.2` 
```
**Output:**

-   Item 1
-   Item 2
    -   Subitem 2.1
    -   Subitem 2.2

### 7. Ordered List of Items

**Markdown Code:**

```

`1. First Item
2. Second Item
3. Third Item` 
```
**Output:**

1.  First Item
2.  Second Item
3.  Third Item

### 8. CheckBox Task List

**Markdown Code:**

```

`- [x] Completed Task
- [ ] Incomplete Task` 
```
**Output:**

-   [x] Completed Task
-  [ ] Incomplete Task

### 9. Blockquote Text

**Markdown Code:**

```

`> Blockquote Text` 
```
**Output:**

> Blockquote Text

### 10. Link

**Markdown Code:**

```

`[Google](https://www.google.com)` 
```
**Output:** [Google](https://www.google.com/)

### 11. Image

**Markdown Code:**

```

`![Alt Text](https://via.placeholder.com/150)` 
```
**Output:**
 ![Alt Text](https://via.placeholder.com/150)

### 12. Linking an Image

**Markdown Code:**

```

`[![Alt Text](https://via.placeholder.com/150)](https://www.google.com)` 
```
**Output:**
 [![Alt Text](https://via.placeholder.com/150)](https://www.google.com/)

### 13. Emojis

**Markdown Code:**

```

`:smile:` 
```
**Output:** 😄

### 14. Horizontal Line

**Markdown Code:**

```

`---` 
```
## **Output:**

### 15. Code

**Markdown Code:**

```

`` `Inline Code` `` 
```
**Output:** `Inline Code`

### 16. Code Block

**Markdown Code:** `
 ``` Code Block 
 Another Line of Code 

**Output:**


`Code Block
Another Line of Code` 

### 17. Table

**Markdown Code:**



| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |` 

**Output:**

| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |` 

### 18. Table With Alignments

**Markdown Code:**



| Left Align | Center Align | Right Align |
|:-----------|:------------:|------------:|
| Cell 1     | Cell 2       | Cell 3      |


**Output:**

| Left Align | Center Align | Right Align |
|:-----------|:------------:|------------:|
| Cell 1     |    Cell 2    |      Cell 3 |


### 19. HTML

**Markdown Code:**


`<b>Bold Text using HTML</b>` 

**Output:** <b>Bold Text using HTML</b>

### 20. Embed YouTube Video

**HTML Code:**

```

`<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>` ```

### 21. Mathematical Expressions

**Markdown Code:**

```

`$$ E = mc^2 $$` 
```
**Output:** $$ E = mc^2 $$

### 22. DropDown (Using HTML)

**HTML Code:**
```

`<details>
  <summary>Title</summary>
  Content here...
</details>` 
```
**Output:**

<details>
  <summary>Title</summary>
  Content here...
</details>

### 23. Diagrams

Markdown itself doesn't support diagrams. You'll need third-party tools or extensions for this. However, some platforms and tools have integrated services like Mermaid or PlantUML to allow for diagram rendering within Markdown. Here's an example using Mermaid syntax:

```mermaid graph TD; A-->B; A-->C; B-->D; C-->D; ```

(Note: The actual rendering of the diagram will depend on the platform's support for Mermaid or other diagram tools.)

For platforms that don't support Mermaid or similar tools, you might need to generate the diagram externally, save it as an image, and then embed the image in your Markdown document.


### 24. FootNote

**Markdown Code:**

```

`Here's a statement[^1].

[^1]: This is the footnote.` 
```
**Output:** Here's a statement[1]([About us bong.dev - Unite, Learn and Code](https://bong.dev/about/)).

### 25. Comments

**Markdown Code:**

```

`[//]: # (This is a comment.)` 
```
**Output:** [//]: # (This is a comment.)

### 26. Nested Blockquotes

You can nest blockquotes by adding additional `>` characters.

**Markdown Code:**

```

`> First Level
>> Second Level
>>> Third Level` 
```
**Output:**

> First Level
> 
> > Second Level
> > 
> > > Third Level

### 27. Inline HTML

You can use any HTML tag inline with your Markdown.

**Markdown Code:**

```

`This is <span style="color:red">red</span> text.` 
```
**Output:** This is <span style="color:red">red</span> text.

### 28. Escaping Characters

If you want to display a character that has a special meaning in Markdown, you can escape it with a backslash (`\`).

**Markdown Code:**

```

`\*This is not italic\*` 
```
**Output:** *This is not italic*

### 29. Reference Links

You can define links and then reference them elsewhere in your document for cleaner Markdown.

**Markdown Code:**

```

`[Google][1]
[GitHub][2]
```
[1]: https://www.google.com
[2]: https://www.github.com` 

**Output:** [Google](https://www.google.com/) [GitHub](https://www.github.com/)

### 30. Reference Images

Just like reference links, but for images.

**Markdown Code:**

```

`![Alt Text][image1]

[image1]: https://via.placeholder.com/150` 
```

**Output:** 
![Alt Text](https://via.placeholder.com/150)

### 31. Abbreviations

Define abbreviations that will show an explanation when hovered over.

**Markdown Code (requires specific Markdown parsers like PHP Markdown Extra):**

```

`The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium` 
```
**Output:** The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language *[W3C]: World Wide Web Consortium

### 32. Definition Lists

Create a list of terms with their corresponding definitions.

**Markdown Code (requires specific Markdown parsers like PHP Markdown Extra):**

```

`Apple
:   A fruit that is red or green.

Orange
:   A juicy citrus fruit.` 
```
**Output:** 
Apple : 
A fruit that is red or green.
Orange : 
A juicy citrus fruit.


### 33. Line Breaks

To create a line break, end a line with two or more spaces, then type return.

**Markdown Code:**

```

`This is the first line.  
This is the second line.` 
```
**Output:** 
This is the first line.  
This is the second line.

## 34. DropDown (Using HTML)

Markdown itself doesn't directly support dropdowns, but you can use HTML within your Markdown to achieve this.

```
<details> <summary>Click to expand!</summary>

Content inside the dropdown.

</details> 
```  
<details> <summary>Click to expand!</summary>

Content inside the dropdown.

</details>
