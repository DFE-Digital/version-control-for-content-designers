# Learning Markdown

Markdown supports a limited number of formatting options by design. It's easy to learn and if you're familiar with [Trello](https://help.trello.com/article/821-using-markdown-in-trello), [Reddit](https://www.reddit.com/wiki/markdown) or [Notion](https://www.notion.so/) you've probably already used it!

## Formatting

### Headings

```markdown
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

---

### Paragraphs

A blank line between two blocks of text will separate them into paragraphs.

```markdown
Vivamus eget ligula eu lacus dignissim gravida. Vestibulum ante ipsum primis in faucibus
orci luctus et ultrices posuere cubilia curae; Proin at ex sit amet nisi pharetra elementum.
In hendrerit eros id molestie mattis.

Ut ullamcorper metus non est lacinia accumsan sed sed sapien. Quisque sed dolor ligula.
Mauris rhoncus ipsum ut sem lobortis, a blandit dui sollicitudin. Nam ut dapibus enim, sit
amet porta diam.
```

Vivamus eget ligula eu lacus dignissim gravida. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Proin at ex sit amet nisi pharetra elementum. In hendrerit eros id molestie mattis.

Ut ullamcorper metus non est lacinia accumsan sed sed sapien. Quisque sed dolor ligula. Mauris rhoncus ipsum ut sem lobortis, a blandit dui sollicitudin. Nam ut dapibus enim, sit amet porta diam.

### Emphasised (italic) text

```markdown
The quick _brown_ fox jumps over the lazy dog
```

The quick _brown_ fox jumps over the lazy dog

### Strong (bold) text

```markdown
The quick brown fox **jumps** over the lazy dog
```

### Strikethrough text

```markdown
The quick brown ~~fox~~ badger jumps over the lazy dog
```

The quick brown ~~fox~~ badger jumps over the lazy dog

### Coded text

```markdown
The quick `#865e3c` fox jumps over the lazy dog
```

The quick `#865e3c` fox jumps over the lazy dog

### Hyperlinks

```markdown
Seach for foxes on [Google](https://www.google.com).
```

Seach for foxes on [Google](https://www.google.com).

### Unordered lists

```markdown
* item 1
* item 2
* item 3
```

* item 1
* item 2
* item 3

### Nested unordered lists

```markdown
* item 1
  * item 1a
    * item 1ai
    * item 1aii
  * item 1b
* item 2
* item 3
```

* item 1
  * item 1a
    * item 1ai
    * item 1aii
  * item 1b
* item 2
* item 3

### Ordered lists

```markdown
1. first
2. second
3. third
```

1. first
2. second
3. third

### Nested ordered lists

```markdown
1. first
	1. first part a
	1. first part b
2. second
	2. second part a
	2. second part b
3. third
```

1. first
	1. first part a
	1. first part b
2. second
	2. second part a
	2. second part b
3. third

### Block quotes

```markdown
> It will have blood, they say. Blood will have blood.
>
> Stones have been known to move, and trees to speak.
>
> Augurs and understood relations have
>
> By maggot pies and choughs and rooks brought forth
>
> The secret'st man of blood.
>
> -- Macbeth, act 3 scene 4
```

> It will have blood, they say. Blood will have blood.
>
> Stones have been known to move, and trees to speak.
>
> Augurs and understood relations have
>
> By maggot pies and choughs and rooks brought forth
>
> The secret'st man of blood.
>
> -- Macbeth, act 3 scene 4

### Embedded images

```markdown
![kittens](https://placekitten.com/400/400)
```

![kittens](https://placekitten.com/400/400)

## Tips for Visual Studio Code users

To preview Markdown documents side-by-side, when you've got a Markdown file open press `Ctrl+k v` (`⌘+k v` on Mac). Note that you need to hold `Ctrl` down while you press `k` but have lifted your finger by the time you press `v`.

The window should now be vertically split with the original document on the left and the rendered output on the right. The preview will automatically update to reflect any changes you make to the original document.

![Visual Studio Code Markdown preview](/images/learning-markdown/vs-code-markdown-preview.png)

## Other tools

* [Typora](https://typora.io/) --- a WYSIWYG Markdown editor for Windows, Mac and Linux

## References and tutorials

* [Markdown tutorial](https://www.markdowntutorial.com/) --- a fun, interactive Markdown tutorial
* [Commonmark](https://commonmark.org/) --- the official Markdown specification
