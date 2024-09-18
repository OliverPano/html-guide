
# HTML Syntax Guide

This guide provides an overview of essential HTML syntax. You will learn how to create various HTML elements and structures.

## 1. Basic HTML Structure
The basic structure of an HTML document consists of the following elements:

1. `<!DOCTYPE html>` declares the document type as HTML5.
2. `<html>` is the root element that contains all other HTML elements.
3. `<head>` includes metadata about the HTML document, such as `<meta charset="UTF-8">` (which sets the character encoding) and `<meta name="viewport">` (which controls the layout on mobile devices).
4. The `<title>` tag inside the `<head>` specifies the document’s title.
5. `<body>` contains the content that is displayed on the web page.

## 2. HTML Tags Overview

### 2.1 Headings
HTML headings are used to define the structure of your document, with `<h1>` being the largest and most important, down to `<h6>` as the smallest heading.

### 2.2 Paragraphs
The `<p>` tag is used for paragraphs, defining blocks of text.

### 2.3 Links
To create hyperlinks, the `<a>` tag is used along with the `href` attribute to define the URL destination.

### 2.4 Images
Images are embedded using the `<img>` tag, which requires two attributes:
- `src`: the image source (URL or file path).
- `alt`: a text description of the image for accessibility.

### 2.5 Lists
There are two types of lists:
- **Unordered lists**: Defined with `<ul>`, each item is wrapped in `<li>`.
- **Ordered lists**: Defined with `<ol>`, items are automatically numbered.

### 2.6 Tables
Tables are defined using the `<table>` tag. Each row is created with `<tr>`, and within rows, you can have header cells (`<th>`) and data cells (`<td>`).

### 2.7 Forms
Forms are used to collect user input. They consist of:
- `<form>`: A container for all form elements, such as text fields, checkboxes, and buttons.
- `<input>`: Defines various types of input fields (`type="text"`, `type="email"`, etc.).
- `<label>`: Provides a label for form elements.

### 2.8 Divs and Spans
- **Div**: A block-level container element used for grouping sections.
- **Span**: An inline container used for styling or grouping small sections of text within a larger block.

## 3. HTML Attributes
HTML attributes provide additional information about elements. Common attributes include:
- `id`: A unique identifier for an element.
- `class`: Used to group elements with the same style or behavior.
- `style`: Adds inline CSS styling to an element.
- `title`: Provides extra information when hovering over an element.

## 4. HTML Comments
HTML comments are enclosed within `<!-- -->` and are ignored by the browser. They are useful for adding notes within the code.

## 5. Special Characters
To display certain reserved HTML characters, you use HTML entities:
- `<` is represented as `&lt;`
- `>` is represented as `&gt;`
- `&` is represented as `&amp;`

## 6. Block vs. Inline Elements

- **Block elements**: These take up the entire width of their container (e.g., `<div>`, `<h1>`, `<p>`).
- **Inline elements**: These take up only as much width as necessary (e.g., `<span>`, `<a>`, `<img>`).

## 7. Self-Closing Tags
Some HTML elements do not require a closing tag, such as:
- `<img>` for images
- `<br>` for line breaks
- `<hr>` for horizontal rules

## 8. Semantic HTML
Semantic HTML provides meaning to web pages and helps with accessibility and SEO. Key semantic tags include:
- `<header>`: Represents the top section of a webpage or article.
- `<nav>`: Represents navigation links.
- `<section>`: Defines a section of related content.
- `<footer>`: Represents the bottom section of a page.

## 9. Embedding Multimedia
- **Audio**: To embed audio, use the `<audio>` tag. It includes controls such as play, pause, and volume.
- **Video**: Videos are embedded using the `<video>` tag with similar controls to audio.

---