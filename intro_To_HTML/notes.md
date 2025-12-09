Updated : 08 Apr, 2025

- 
- 
- 

**HTML** stands for **HyperText Markup Language**. It is the standard language used to create and structure content on the web. It defines the structure of a webpage by using a series of elements, tags, and attributes to organize text, images, links, and other multimedia elements.

- HTML is a markup language, not a programming language, meaning it annotates text to define how it is structured and displayed by web browsers.
- It forms the building blocks of all websites and is complemented by CSS for style and JavaScript for interactivity.
- It is a **static language**, meaning that it does not inherently provide interactive features but can be combined with [**CSS**](https://www.geeksforgeeks.org/css-tutorial/) for styling and [**JavaScript**](https://www.geeksforgeeks.org/javascript/) for interactivity.

In a nutshell, HTML is all about **organizing and displaying information** on a webpage. We can think of it as the **bones** or **structure** of a webpage.

# Basic HTML Code Example

`<!DOCTYPE html>
<**html**>

<**head**>
    <**title**>My First Webpage</**title**>
</**head**>

<**body**>
    <**h1**>Welcome to My Webpage</**h1**>
    <**p**>This is my first paragraph of text!</**p**>
</**body**>

</**html**>`

**Output:**

![](https://media.geeksforgeeks.org/wp-content/uploads/20250408131626705390/Screenshot-2025-04-08-131602.png)

*HTML*

**In this example:**

- **<!DOCTYPE html>**: Declares the document type and version (HTML5).
- **<html>**: The root element that wraps all HTML content.
- **<head>**: Contains meta-information about the webpage, like the title.
- **<title>:** Specifies the title of the webpage (appears in the browser tab).
- **<body>**: Contains the visible content of the webpage.
- **<h1>**: Represents the main heading on the page (“Welcome to My Webpage”).
- **<p>**: Defines a paragraph of text (“This is my first paragraph of text!”).

![](https://media.geeksforgeeks.org/wp-content/uploads/20250408124045617486/HTML-intoduction.webp)

*HTML Introduction*

# Key Features of HTML

- **Markup Language:** HTML uses tags to markup content. Each tag defines different elements, such as headings, paragraphs, tables, links, etc.
- **Semantics:** HTML provides semantic tags that describe the meaning of the content. For example, <article>, <footer>, <header>, and <nav> describe different types of content on a webpage.
- **Responsive Web Design**: HTML supports various features for building responsive websites, including media queries and the ability to embed multimedia content.
- **Interactive Content:** HTML can embed interactive content using JavaScript, which allows for dynamic changes in the content.

# HTML Page Structure

The basic structure of an HTML page is shown below. It contains the essential building-block elements (i.e. doctype declaration, HTML, head, title, and body elements) upon which all web pages are created.

![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20220401160946/HTML-Basic-Format-768x534.png)

- [**<!DOCTYPE html>**](https://www.geeksforgeeks.org/html-doctypes/) – This is the document type declaration, not a tag. It declares that the document is an HTML5 document.
- [**<html>**](https://www.geeksforgeeks.org/html-html-tag/) – This is called the HTML root element. All other elements are contained within it.
- [**<head>**](https://www.geeksforgeeks.org/html-head-tag/) – The head tag contains the “behind the scenes” elements for a webpage. Elements within the head aren’t visible on the front end of a webpage. Typical elements inside the <head> include:
    - [**<title>](https://www.geeksforgeeks.org/html-title-tag/):** Defines the title displayed on the browser tab.
    - [**<meta>**](https://www.geeksforgeeks.org/html-meta-tag/): Provides information like the character set or viewport settings.
    - [**<link>**](https://www.geeksforgeeks.org/html-link-tag/): Links external stylesheets or resources.
    - [**<style>**](https://www.geeksforgeeks.org/html-style-tag/): Embeds internal CSS styles.
    - [**<script>**](https://www.geeksforgeeks.org/html-script-tag/): Embeds JavaScript for functionality.
- [**<title>**](https://www.geeksforgeeks.org/html-title-tag/) – The title is what is displayed on the top of your browser when you visit a website and contains the title of the webpage that you are viewing.
- **<h2>** – The <h2> tag is a second-level heading tag.
- [**<p>**](https://www.geeksforgeeks.org/html-p-tag/)– The <p> tag represents a paragraph of text.
- [**<body>**](https://www.geeksforgeeks.org/html-body-tag/) – The body tag is used to enclose all the visible content of a webpage. In other words, the body content is what the browser will show on the front end.

An HTML document can be created using an [**HTML text editor**](https://www.geeksforgeeks.org/html-editors/). Save the text file using the “**.html”** or “**.htm”** extension. Once saved as an HTML document, the file can be opened as a webpage in the browser.

> Note: Basic/built-in text editors are Notepad (Windows) and TextEdit (MacOS). Other advanced text editors include Sublime Text, Visual Studio Code, Froala, etc.
> 

# HTML Elements and HTML Tag

HTML Elements and HTML Tags are related but distinct. An **HTML** **element** is the complete structure, including the opening tag, content (if any), and the closing tag (if applicable).

On the other hand, A **tag** is the actual keyword or name enclosed in angle brackets (`< >`) that tells the browser what kind of content to expect.

![](https://media.geeksforgeeks.org/wp-content/uploads/20250408124306294228/Screenshot-2025-04-08-124248.png)

*HTML Tags*

| **Tag** | **Description** |
| --- | --- |
| **<html>** | The root element of an HTML document |
| [**<head>**](https://www.geeksforgeeks.org/html-head-tag/?ref=ml_lbp) | Contains meta-information about the webpage |
| [**<body>**](https://www.geeksforgeeks.org/html-body-tag/) | Contains the visible content of the webpage |
| [**<h1> to <h6>**](https://www.geeksforgeeks.org/html-h1-to-h6-tag/) | Headings of various levels (h1 being the largest) |
| **<p>** | Defines a paragraph |
| **<a>** | Defines a hyperlink |
| [**<img>**](https://www.geeksforgeeks.org/html-img-tag/) | Embed an image |
| [**<ul>**](https://www.geeksforgeeks.org/html-ul-tag/) | Defines an unordered list |
| [**<ol>**](https://www.geeksforgeeks.org/html-ol-tag/) | Defines an ordered list |
| [**<li>**](https://www.geeksforgeeks.org/html-li-tag/) | Defines a list item |
| [**<table>**](https://www.geeksforgeeks.org/html-tables/) | Defines a table |
| [**<form>**](https://www.geeksforgeeks.org/html-forms/) | Defines an HTML form |

> To learn more about it follow the article – HTML Tags
> 

# HTML Attributes

Attributes provide additional information about an element. They are placed inside the opening tag and are written as name=”value”. Common attributes include class, id, href, and src.

**Example:**

```
<a href="https://www.example.com">Visit Example</a>
```

- href is an attribute of the <a> tag that defines the URL of the link.

> To learn more about it follow the article – HTML Attributes
> 

# Web Browsers

Unlike other programming languages, HTML does not show output on the compiler. [**Web browsers**](https://www.geeksforgeeks.org/web-browser-a-complete-overview/) show the results of an HTML code.

It reads HTML files and determines how to show content with the help of HTML tags. Any web browser (**Google, Safari, Mozilla Firefox**, etc) can be used to open a **. HTML file** and view the results.

![](https://media.geeksforgeeks.org/wp-content/uploads/20241122150935140993/Screenshot-2024-11-22-150453.png)

*index.html*

# Why Learn HTML?

Here are **5 common reasons to learn HTML**:

1. **Build Websites**: HTML is the basic building block for creating any website. Learning HTML can help you pursue a career in web development.
2. **Customize Content**: Allows you to edit or tweak web pages, emails, or templates to fit your needs.
3. **Understand how the web works**: This helps you grasp how the internet works and how web pages are structured.
4. **Employment Opportunities**: According to the Bureau of Labor Statistics, projects that employment for web developers will grow 16% between 2022 and 2032, which is much faster than the average across all occupations.
5. **Learn Easily**: HTML is beginner-friendly, making it a great first step into the world of coding and technology.

# Applications of HTML

- **Web Development:** HTML is the backbone of every webpage. It structures the content and integrates multimedia, hyperlinks, and more.
- **Web Applications:** HTML, in combination with CSS and JavaScript, powers complex web applications (e.g., Google Docs, Trello).
- **Emails:** HTML emails use table-based layouts and embedded media to deliver rich, interactive content.
- **Mobile App Development:** HTML5 is used with frameworks like PhoneGap to build mobile apps for iOS and Android.

# Limitations of HTML

- **No Logic or Functionality:** HTML cannot handle complex logic, interactivity, or dynamic content on its own. It requires JavaScript for such tasks.
- **SEO Limitations:** While HTML provides structure, it’s not enough by itself for search engine optimization (SEO). Proper metadata and content structuring, as well as external SEO practices, are necessary.
- **Limited Styles:** While HTML can handle basic styles via the style attribute, it is typically complemented by CSS for complex styling and layout.

# HTML5: Enhancements and New Features

HTML5 introduced several powerful features that improve the structure and functionality of web pages, including:

- **Semantics:** New tags like <article>, <footer>, <header>, and <section> to improve the meaning of the content.
- **Multimedia**: <audio> and <video> tags for embedding audio and video without plugins.
- **APIs:** New APIs like Geolocation, Web Storage, and Canvas allow for more dynamic content and interactive websites.

# HTML History

Currently, we are using [**HTML5**](https://www.geeksforgeeks.org/html5-introduction/), which is the latest and most advanced version of HTML.

- HTML was initially created by **Tim Berners-Lee** in 1991 as a way to share and structure documents on the web.
- The first-ever version was **HTML 1.0**, a basic and limited version. However, the first standardized version, **HTML 2.0**, was published in 1995, laying the foundation for web development as we know it today.

![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20220718103358/HTML-Released-year-11.png)

# Conclusion

In conclusion, mastering HTML is a fundamental step in your web development journey. This guide serves as a comprehensive resource for understanding HTML, from the basics to more advanced topics. Remember, HTML is more than just a markup language – it’s a powerful tool for creating engaging, accessible, and SEO-friendly websites.

To learn more about HTML, visit the [**HTML Tutorial**](https://www.geeksforgeeks.org/html-tutorial/) Page.

> Master The Art of Web Development with Full Stack Web Development
>