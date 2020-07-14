# About The Session - "Web Development Basics and HTML"
<img src="https://img.shields.io/badge/HTML-Code-orange"> <img src="https://img.shields.io/badge/HTML-Documentation-brightgreen"> <img src="https://img.shields.io/badge/License-MIT-red">

This session revolves around the basics of web, ranging from what browser,server,internet are. 
We will be giving a brief overview of how structuring of webpage is done using HTML.

## About the Documentation

This is the **Cheat Sheet** opened for everyone to use during the hackathon. There are resources and tools embeded inside which you can use as a participant.

## Softwares And Installations

You can install any of these Editors,
* [Sublime Text](https://www.sublimetext.com/) <img src="https://img.shields.io/badge/Editor-Sublime-yellow">
* [Atom](https://atom.io/) [Preferable, will be using in the session] <img src = https://img.shields.io/badge/Editor-Atom-green>
* NotePad - May Be present in your system already
* One [GitHub](https://github.com/) account
* Any of the browsers - Like Chrome, Safari,Opera etc.

## Content

You can find the slides here - <a href = "https://www.canva.com/design/DAEBAah68is/share/preview?token=d58aB02L1p3sE-Aidi1LBQ&role=EDITOR&utm_content=DAEBAah68is&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton">Slides</a>

* [How Does The Internet Work](https://github.com/Abhijit2505/Front-End-Hackathon-Resources/blob/master/First%20Session/DOC.md#how-does-the-internet-work-)
* [What is HTML](https://github.com/Abhijit2505/Front-End-Hackathon-Resources/blob/master/First%20Session/DOC.md#what-is-html-)
* <details><summary><a href="https://github.com/Abhijit2505/Front-End-Hackathon-Resources/blob/master/First%20Session/DOC.md#tags-and-elements-cheatsheet">Tags and Elements Cheatsheet</a></summary>
   
    * [comments](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#comments)
    * [html](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#html)
    * [head](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#head)
    * [body](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#body)
    * [heading](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#heading)
    * [paragraph](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#paragraph)
    * [br](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#br)
    * [anchor](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#anchor)
    * [img](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#img)
    * [list](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#list)
    * [Text Formatting](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#text-formatting)</details> 
    
   * <details><summary><a href="https://github.com/Abhijit2505/Front-End-Hackathon-Resources/tree/master/First%20Session#some-intermediate-stuffs">Some Intermediate Stuffs</a></summary>
   
   
      * [Making HTML Table Element](https://github.com/Girlscript-Chapter-Bilaspur/Front-End-Hackathon-Resources/tree/master/First%20Session#making-html-table-element)</details>



### How Does The Internet Work ?

The Internet is made up of a massive network of specialized computers called routers. Each router’s job is to know how to move packets along from 
their source to their destination. A packet will have moved through multiple routers during its journey.

Along with the session slides, here is an addition from [Medium](https://medium.com/), Have a visit to the link - [How Does The Internet Work?](https://medium.com/@User3141592/how-does-the-internet-work-edc2e22e7eb8#:~:text=The%20Internet%20is%20made%20up,next%2C%20it's%20called%20a%20hop.)
to get an entire overview of how the internet works.

### What is HTML ?

* **HTML** stands for **Hypertext Markup Language**. It allows the user to create and structure sections, paragraphs, headings, links, and blockquotes 
for web pages and applications.

* HTML is not a programming language, meaning it doesn’t have the ability to create dynamic functionality. Instead, it makes it possible to organize 
and format documents, similarly to Microsoft Word. That's why it is known as **Mark Up Language**.
* HTML documents are files that end with a **.html** or **.htm** extension. You can view then using any **web browser** (such as Google Chrome, Safari, or Mozilla Firefox). 
The browser reads the HTML file and renders its content so that internet users can view it.
* Usually, the average website includes several different **HTML pages**. For instance: home pages, about pages, contact pages would all have separate HTML documents.
* Each HTML page consists of a set of **tags** (also called elements), which you can refer to as the building blocks of web pages. 
They create a hierarchy that structures the content into sections, paragraphs, headings, and other content blocks.

* Most HTML elements have an opening and a closing that use the ```<tag></tag>``` syntax.

### Tags and Elements CheatSheet

#### comments

```<!--comments--->``` is used to add comments.

#### html

The ```<html></html>``` represents the root (top-level element) of an HTML document, so it is also referred to as the root element. 
All other elements must be descendants of this element.

**Example**

    <!DOCTYPE html>
    <html lang="en">
      <head>...</head>
      <body>...</body>
    </html>
    
Providing a **lang** attribute with a valid IETF identifying language tag on the html element will help 
screen reading technology determine the proper language to announce. The identifying language tag should describe 
the language used by the majority of the content of the page. Without it, screen readers will
typically default to the operating system's set language, which may cause mispronunciations.

Including a valid **lang** declaration on the html element also ensures that important metadata contained in the page's 
```<head>```, such as the page's ```<title>```, are also announced properly.

#### head

The ```<head>``` provides general information (metadata) about the document, including its title and links to its scripts and style sheets.

**Example**

    <html>
      <head>
        <title>Document title</title>
      </head>
    </html>

The HTML Title element ```<title>``` defines the document's title that is shown in a browser's title bar or a page's tab. 
It only contains text and tags within the element are ignored.

#### body

The ```<body>``` represents the content of an HTML document. There can be only one ```<body>``` element in a document.

**Example**

    <html>
      <head>
        <title>Document title</title>
      </head>
      <body>
        <p>This is a paragraph</p>
      </body>
    </html>

#### heading

This one is used to create headings with six different tags ranging from **h1** to **h6**, Have a look at the example below,

**Example**

    <h1>Heading level 1</h1>
    <h2>Heading level 2</h2>
    <h3>Heading level 3</h3>
    <h4>Heading level 4</h4>
    <h5>Heading level 5</h5>
    <h6>Heading level 6</h6>

<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>

#### paragraph

The ```<p>``` represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank
lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields.

**Example**

    <p>This is the first paragraph of text.
      This is the first paragraph of text.
      This is the first paragraph of text.
      This is the first paragraph of text.</p>
    <p>This is the second paragraph.
      This is the second paragraph.
      This is the second paragraph.
      This is the second paragraph.</p>

#### br

The ```<br>``` produces a line break in text (carriage-return). It is useful for writing a poem or an address, where the division of lines is significant.

**Example**

    GirlScript Bilaspur<br>
    Bilaspur,Chhattisgarh<br>
    123456<br>
    India<br>

GirlScript Bilaspur<br>
Bilaspur,Chhattisgarh<br>
123456<br>
India<br>

#### anchor

The ```<a>``` (or anchor element) creates a hyperlink to other web pages, files, locations within the same page, email addresses, or any other URL.

**Example**

    <a href="https://girlscript-chapter-bilaspur.github.io/Forntend-Hackathon/">
    External Link
    </a>   

<a href="https://girlscript-chapter-bilaspur.github.io/Forntend-Hackathon/">
External Link
</a>   

##### Common Attributes - 
##### href
Contains a URL or a URL fragment that the hyperlink points to.
A URL fragment is a name preceded by a hash mark (#), which specifies an internal target location (an ID of an HTML element) within the current document. URLs are not restricted to Web (HTTP)-based documents, but can use any protocol supported by the browser. For example, file:, ftp:, and mailto: work in most browsers.
You can use href="#top" or the empty fragment href="#" to link to the top of the current page. This behavior is specified by HTML5.

##### rel
Specifies the relationship of the target object to the link object. The value is a space-separated list of link types.

##### target
Specifies where to display the linked URL. It is a name of, or keyword for, a browsing context: a tab, window, or <iframe>. The following keywords have special meanings:
* **_self**: Load the URL into the same browsing context as the current one. This is the default behavior.
* **_blank**: Load the URL into a new browsing context. This is usually a tab, but users can configure browsers to use new windows instead.
* **_parent**: Load the URL into the parent browsing context of the current one. If there is no parent, this behaves the same way as _self.
* **_top**: Load the URL into the top-level browsing context (that is, the "highest" browsing context that is an ancestor of the current one, and has no parent). If there is no parent, this behaves the same way as _self.

#### img

The ```<img>``` embeds an image into the document. It is a replaced element.

**Example**

    <img src="book_photo.png" alt="A Book Photo">

##### Common Attributes - 

#### alt
This attribute defines an alternative text description of the image.
Note: Browsers do not always display the image referenced by the element. This is the case for non-graphical browsers 
(including those used by people with visual impairments), if the user chooses not to display images, or if the browser 
cannot display the image because it is invalid or an unsupported type. In these cases, the browser may replace the image 
with the text defined in this element's alt attribute. You should, for these reasons and others, provide a useful value for 
alt whenever possible.

#### height
The intrinsic height of the image in pixels.

#### src
The image URL. This attribute is mandatory for the <img> element. On browsers supporting srcset,
src is treated like a candidate image with a pixel density descriptor 1x unless an image with this 
pixel density descriptor is already defined in srcset, or unless srcset contains 'w' descriptors.

#### width
The intrinsic width of the image in pixels.

#### list

```<li></li>``` is used to create items in a list.

##### unorderd list
The ```<ul>``` represents an unordered list of items, typically rendered as a bulleted list.

**Example**

      <ul>
        <li>first item</li>
        <li>second item</li>
        <li>third item</li>
      </ul>

<ul>
        <li>first item</li>
        <li>second item</li>
        <li>third item</li>
      </ul>

##### ordered list
The ```<ol>``` represents an ordered list of items, typically rendered as a numbered list.

**Example**

    <ol>
      <li>first item</li>
      <li>second item</li>
      <li>third item</li>
    </ol>

<ol>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ol>

#### Text Formatting

* BOLD TEXT ```<b>---</b>```
* BIG TEXT ```<big>---</big>```
* ITALIC TEXT ```<i>---</i>```
* SMALL TEXT ```<small>---</small>```
* STRONG TEXT ```<strong>---</strong>```
* SUBSCRIPTED TEXT ```<sub>---</sub>```
* SUPERSCRIPTED TEXT ```<sup>---</sup>```
* INSERTED TEXT ```<ins>---</ins>```
* DELETED TEXT ```<del>---</del>```

#### Some Intermediate Stuffs

##### Making HTML Table Element

**Example**

      <table border='1'>
            <thead>
              <tr>
                <td>
                  <em><b>Name</b></em>
                </td>
                <td>
                  <em><b>Place</b></em>
                </td>
                <td>
                  <em><b>Mobile Number</b></em>
                </td>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>
                  Abhijit
                </td>
                <td>
                  Bilaspur
                </td>
                <td>
                  1234567891484
                </td>
              </tr>
            </tbody>
            <tbody>
              <tr>
                <td>
                  Ruhi
                </td>
                <td>
                  Bilaspur
                </td>
                <td>
                  9856224744714
                </td>
              </tr>
            </tbody>
            <tbody>
              <tr>
                <td>
                  Abhishek
                </td>
                <td>
                  Bilaspur
                </td>
                <td>
                  1484548145141
                </td>
              </tr>
            </tbody>
            <tbody>
              <tr>
                <td>
                  Ajay
                </td>
                <td>
                  Bilaspur
                </td>
                <td>
                  1489464965494
                </td>
              </tr>
            </tbody>
            <tbody>
              <tr>
                <td>
                  Deepesh
                </td>
                <td>
                  Bilaspur
                </td>
                <td>
                  5545415845454
                </td>
              </tr>
            </tbody>
          </table>


<table border='1'>
      <thead>
        <tr>
          <td>
            <em><b>Name</b></em>
          </td>
          <td>
            <em><b>Place</b></em>
          </td>
          <td>
            <em><b>Mobile Number</b></em>
          </td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            Abhijit
          </td>
          <td>
            Bilaspur
          </td>
          <td>
            1234567891484
          </td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td>
            Ruhi
          </td>
          <td>
            Bilaspur
          </td>
          <td>
            9856224744714
          </td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td>
            Abhishek
          </td>
          <td>
            Bilaspur
          </td>
          <td>
            1484548145141
          </td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td>
            Ajay
          </td>
          <td>
            Bilaspur
          </td>
          <td>
            1489464965494
          </td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td>
            Deepesh
          </td>
          <td>
            Bilaspur
          </td>
          <td>
            5545415845454
          </td>
        </tr>
      </tbody>
    </table>

**Explanation Of Tags**

* ```<table></table>``` - The ```<table>``` represents tabular data — that is, information presented in a two-dimensional 
table comprised of rows and columns of cells containing data.
* ```<thead></thead>``` - The <thead> defines a set of rows defining the head of the columns of the table.
* ```<tbody></tbody>``` - The HTML Table Body element (<tbody>) encapsulates a set of table row (<tr> elements), 
indicating that they comprise the body of the table (<table>).
* ```<tr></tr>``` - The ```<tr>``` defines a row of cells in a table. The row's cells can then be established using a mix of ```<td>``` (data cell) and ```<th>``` (header cell) elements.

##### HTML form element

      <form action="" method="get" class="form-example">
        <div class="form-example">
          <label for="name">Enter your name: </label>
          <input type="text" name="name" id="name" required>
        </div>
        <div class="form-example">
          <label for="email">Enter your email: </label>
          <input type="email" name="email" id="email" required>
        </div>
        <div class="form-example">
          <input type="submit" value="Follow Me">
        </div>


**Explanation Of Tags**

* **action** - The URI of a program that processes the form information. This value can be overridden by a formaction attribute on a ```<button>``` or ```<input>``` element.
* **name** - The name of the form
* **target** - A name or keyword indicating where to display the response that is received after submitting the form. In HTML 4, this is the name/keyword for a frame. In HTML5, it is a name/keyword for a browsing context (for example, tab, window, or inline frame). The following keywords have special meanings:
   * **_self**: Load the response into the same HTML 4 frame (or HTML5 browsing context) as the current one. This value is the default if the attribute is not specified.
   * **_blank**: Load the response into a new unnamed HTML 4 window or HTML5 browsing context.
   * **_parent**: Load the response into the HTML 4 frameset parent of the current frame, or HTML5 parent browsing context of the current one. If there is no parent, this option behaves the same way as ```_self```.
   * **_top**: HTML 4: Load the response into the full original window, and cancel all other frames. HTML5: Load the response into the top-level browsing context (i.e., the browsing context that is an ancestor of the current one, and has no parent). If there is no parent, this option behaves the same way as ```_self```.
   * **iframename**: The response is displayed in a named ```<iframe>```.
* **method** - The HTTP method that the browser uses to submit the form. Possible values are:
   * **post**: Corresponds to the HTTP POST method ; form data are included in the body of the form and sent to the server.
   * **get**: Corresponds to the HTTP GET method; form data are appended to the action attribute URI with a ```?``` as separator, and the resulting URI is sent to the server. Use this method when the form has no side-effects and contains only ASCII characters.
This value can be overridden by a formmethod attribute on a ```<button>``` or ```<input>``` element.

For more details on HTML forms, please visit - [HTML Design Forms](https://www.geeksforgeeks.org/html-design-form/)

#### References

* [DevDocs](https://devdocs.io/)
* [Mozilla Developer Network](https://developer.mozilla.org/en-US/)
* [W3 Schools](https://www.w3schools.com/)

#### Contributors 

* [Shalu Kumari](https://www.linkedin.com/in/shalu-kumari-42ab8019b/)
* [Prashashti Pankaj](https://www.linkedin.com/in/prashasti-pankaj-8875a8171/)
* [Abhijit Tripathy](https://www.linkedin.com/in/abhijit-tripathy-415912187/) <a href="https://github.com/Abhijit2505"><img src = "https://img.shields.io/badge/Follow-4183C4?logo=github&style=social"></a>


















