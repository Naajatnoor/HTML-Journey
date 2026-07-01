# HTML Basics Notes

## What is HTML?

**HTML (HyperText Markup Language)** is the standard markup language used to create and structure web pages. It uses **tags** to organize and display content such as headings, paragraphs, images, links, tables, and forms.

---

# Basic HTML Document Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>

<body>

    Content goes here.

</body>
</html>
```

### Explanation

* `<!DOCTYPE html>` → Tells the browser that this document uses HTML5.
* `<html>` → The root element of an HTML document.
* `<head>` → Contains information about the webpage (metadata).
* `<title>` → Sets the title shown in the browser tab.
* `<body>` → Contains all the visible content of the webpage.

---

# Common HTML Tags

## `<p>` — Paragraph Tag

The `<p>` tag is used to create a paragraph.

**Example**

```html
<p>This is a paragraph.</p>
```

---

## `<br>` — Line Break Tag

The `<br>` tag creates a line break. It is an empty tag and does not require a closing tag.

**Example**

```html
First Line<br>
Second Line
```

---

## `<hr>` — Horizontal Rule Tag

The `<hr>` tag creates a horizontal line that separates sections of a webpage.

**Example**

```html
<hr>
```

---

## `<b>` — Bold Tag

The `<b>` tag displays text in bold without indicating special importance.

**Example**

```html
<b>Bold Text</b>
```

---

## `<strong>` — Strong Tag

The `<strong>` tag displays text in bold and indicates that the text is important.

**Example**

```html
<strong>Important Text</strong>
```

---

## `<i>` — Italic Tag

The `<i>` tag displays text in italic.

**Example**

```html
<i>Italic Text</i>
```

---

## `<em>` — Emphasis Tag

The `<em>` tag displays text in italic and indicates emphasis.

**Example**

```html
<em>Emphasized Text</em>
```

---

## `<u>` — Underline Tag

The `<u>` tag displays underlined text.

**Example**

```html
<u>Underlined Text</u>
```

---

## `<del>` — Deleted Tag

The `<del>` tag displays text with a line through it.

**Example**

```html
<del>Old Price</del>
```

---

## `<mark>` — Mark Tag

The `<mark>` tag highlights text.

**Example**

```html
<mark>Highlighted Text</mark>
```

---

## `<small>` — Small Tag

The `<small>` tag displays text in a smaller font size.

**Example**

```html
<small>Small Text</small>
```

---

## `<sub>` — Subscript Tag

The `<sub>` tag displays text slightly below the normal line.

**Example**

```html
H<sub>2</sub>O
```

---

## `<sup>` — Superscript Tag

The `<sup>` tag displays text slightly above the normal line.

**Example**

```html
x<sup>2</sup>
```

---

# Heading Tags

HTML provides six heading tags.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

### Notes

* `<h1>` is the largest and most important heading.
* `<h6>` is the smallest and least important heading.
* Headings help organize webpage content and improve readability.

---

# Important Notes

* Every HTML document should have only **one** `<html>` tag.
* Every HTML document should have only **one** `<body>` tag.
* Use lowercase letters when writing HTML tags (recommended).
* HTML tags usually have an opening tag and a closing tag.
* Some tags, such as `<br>` and `<hr>`, are empty tags and do not have closing tags.

---

# Summary

* HTML is used to create web pages.
* HTML uses tags to structure content.
* `<html>` is the root element.
* `<head>` stores metadata.
* `<body>` contains all visible content.
* `<p>` creates paragraphs.
* `<br>` inserts a line break.
* `<hr>` creates a horizontal line.
* `<b>` and `<strong>` make text bold.
* `<i>` and `<em>` make text italic.
* `<u>` underlines text.
* `<del>` shows deleted text.
* `<mark>` highlights text.
* `<small>` makes text smaller.
* `<sub>` displays subscript text.
* `<sup>` displays superscript text.
* HTML provides six heading tags: `<h1>` to `<h6>`.

