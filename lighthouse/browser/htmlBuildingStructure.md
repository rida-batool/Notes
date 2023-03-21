# Building Structure

![](image/html5.PNG)

## Header

The <header\> element, like it sounds, is used to identify the top of a page, article, section, or other segment of a page. In general, the <header\> element may include a heading, introductory text, and even navigation.

```
<header>...</header>
```

## Differences

![](image/diff.PNG)

## Navigation

Used to link to other pages or just use it for major navigation. Like table of contents, next page/previous page.
One off links should be wrapped in anchor element. <a\>

```
<nav>...</nav>
```

## Article

The <article\> element is used to identify a section of independent, self-contained content that may be independently distributed or reused.

If the content of article is placed somewhere else for reuse like email, it should still make sense without the context of previous page. Than you cane use article.

```
<article>...</article>
```

## Section

The <section\> element is used to identify a thematic grouping of content, which generally, but not always, includes a heading.

The <section\> element is commonly used to break up and provide hierarchy to a page.

```
<section>...</section>
```

## Important

---

Decide between article, section and div elements

Use <article\> when the contents can be **reused** independently.

Use <section\> when content adds to the document outline and represents a **thematic** group of content.

Use <div\> when the contents grouped are for **styling purposes**. Dive do not provide value to outline of document.

---

## Aside

The <aside\> element holds content, such as sidebars, inserts, or brief explanations, that is tangentially related to the content surrounding it.

```
<aside>...</aside>
```

## Footer

The <footer\> element identifies the closing or end of a page, article, section, or other segment of a page.

```
<footer>...</footer>
```
