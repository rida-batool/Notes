# Setting Up the HTML Document Structure

HTML documents are plain text documents saved with an .html file extension rather than a .txt file extension.

All HTML documents have a required structure that includes the following declaration and elements:

```
<!DOCTYPE html>, <html>, <head>, and <body>.
```

**\<!DOCTYPE html\>, informs web browsers which version of HTML is being used and is placed at the very beginning of the HTML document.**

**\<html\> element signifies the beginning of the document.**

Inside the \<html\> element, the <head> element identifies the top of the document, including any metadata (accompanying information about the page).

**The content inside the \<head\> element is NOT displayed on the web page itself.**

Instead, it may include the document title (which is displayed on the title bar in the browser window), links to any external files, or any other beneficial metadata.

All of the visible content within the web page will fall within the \<body\> element. A breakdown of a typical HTML document structure looks like this:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Hello World</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>This is a web page.</p>
  </body>
</html>
```
