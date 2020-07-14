# About The Session - "Bootstrap Framework"
<img src="https://img.shields.io/badge/Bootstrap-Code-orange"> <img src="https://img.shields.io/badge/Bootstrap-Documentation-brightgreen"> <img src="https://img.shields.io/badge/License-MIT-red">

This session revolves around the basics of framework, tools and layout, bootstrap - (Intro, History, Why we use Bootstrap, Advantages & Disadvantages, Components, Grid System, Navbar, Portfolio page).
We will be giving a brief overview of how structuring of webpage is done using Bootstrap.

For Official Documentation, Visit - https://getbootstrap.com/docs/4.5/getting-started/introduction/

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

You can find the slides here - <a href = "https://www.canva.com/design/DAEB5rW7RFg/IKKunaSpzpFh_4liAbIh8w/view?utm_content=DAEB5rW7RFg&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink">Slides (Click Here For Presentation Slides !</a>

### Presentation Slides Contain these topics - 

* Front - End Framework
* Tools and layout
* Bootstrap Intro & History
* Boostrap Package
* Responsive Design
* Advantages and Disadvatages
* Bootstrap Loading
* Common Bootstap Components
* Grid System


### Bootstrap - 

* Bootstrap is a free front-end framework for faster and easier web development.
* Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins.
* Bootstrap also gives you the ability to easily create responsive designs.

### How to include boostrap file in HTML ?

#### 1. Using Bootstrap CDN

If you don't want to download and host Bootstrap 4 yourself, you can include it from a CDN (Content Delivery Network).
You can find it here, visit - https://getbootstrap.com/docs/4.5/getting-started/introduction/

**OR**

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
```

You have Copy-paste the stylesheet ```<link>``` into your ```<head>``` before all other stylesheets to load our CSS.


Many of our components require the use of JavaScript to function. Specifically, they require jQuery, Popper.js, and our own JavaScript plugins.

```html
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
```

Copy and paste the following ```<script>```s near the end of your pages, right before the closing ```</body>``` tag, to enable them. jQuery must come first, then Popper.js, and then our JavaScript plugins.


#### 2. Downloading the files locally

Instead of using cdn, you can download the files locally to your project folder from https://github.com/twbs/bootstrap/releases/download/v4.5.0/bootstrap-4.5.0-dist.zip

Once you download the file, you can include bootstrap.min.css file in the ```<head>``` and bootstrap.min.js in ```<body>```. Even if you are using the downloaded bootstrap file, you have to include jquery.min.js and popper.min.js before loading bootstrap.min.js

### Bootstrap Starter Template

```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
  </body>
</html>
```

### How to add buttons in HTML file with the help of Bootstrap?

For Button Documentation, Visit - https://getbootstrap.com/docs/4.5/components/buttons/

Example - 
```html
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Light</button>
<button type="button" class="btn btn-dark">Dark</button>

<button type="button" class="btn btn-link">Link</button>
```
![](https://github.com/abhishekapk/Front-End-Hackathon-Resources/blob/master/Third%20Session/Assests/buttons.JPG)


### How to add Jumpotrons in HTML file with the help of Bootstrap?

A lightweight, flexible component that can optionally extend the entire viewport to showcase key marketing messages on your site.

For Button Documentation, Visit - https://getbootstrap.com/docs/4.5/components/jumbotron/

![](https://github.com/abhishekapk/Front-End-Hackathon-Resources/blob/master/Third%20Session/Assests/jumpo.JPG)
```html
<div class="jumbotron">
  <h1 class="display-4">Hello, world!</h1>
  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
  <hr class="my-4">
  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
  <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
</div>
```

### Boostrap Navbar !

Documentation and examples for Bootstrap’s powerful, responsive navigation header, the navbar. Includes support for branding, navigation, and more, including support for our collapse plugin.

#### How it works?
Here’s what you need to know before getting started with the navbar:
* Navbars require a wrapping ```.navbar``` with ```.navbar-expand{-sm|-md|-lg|-xl}``` for responsive collapsing and color scheme classes.
* Navbars and their contents are fluid by default. Use optional containers to limit their horizontal width.
* Use our spacing and flex utility classes for controlling spacing and alignment within navbars.
* Navbars are responsive by default, but you can easily modify them to change that. Responsive behavior depends on our Collapse JavaScript plugin.
* Navbars are hidden by default when printing. Force them to be printed by adding .d-print to the .navbar. See the display utility class.
* Ensure accessibility by using a ```<nav>``` element or, if using a more generic element such as a ```<div>```, add a ```role="navigation"``` to every navbar to explicitly identify it as a landmark region for users of assistive technologies.

![](https://github.com/abhishekapk/Front-End-Hackathon-Resources/blob/master/Third%20Session/Assests/navbar.JPG)

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
```

For documentation of Navbar, Visit - https://getbootstrap.com/docs/4.5/components/navbar/

### Bootstrap Grid System - 
* The Bootstrap grid is a table containing rows and columns sustaining the capability to utilize a 12-column grid that is responsive.
* Grid column elements are placed inside row elements, which create horizontal groups of columns. You can have as many rows as you want on the page, but columns must be immediate children of rows. In a full row, the column widths will be any combination that adds up to 12, but it is not mandatory to use all 12 available columns.
* The columns will re-arrange automatically depending on the screen size.
* It uses a series of containers, rows, and columns to layout and align content.


*Boostrap Grid System Documentation, Visit -* https://getbootstrap.com/docs/4.5/layout/grid/

See how aspects of the Bootstrap grid system work across multiple devices with a handy table.<br>
![](https://github.com/abhishekapk/Front-End-Hackathon-Resources/blob/master/Third%20Session/Assests/grid.JPG)

Example - 

```html
<div class="container">
  <div class="row">
    <div class="col">
      1 of 2
    </div>
    <div class="col">
      2 of 2
    </div>
  </div>
  <div class="row">
    <div class="col">
      1 of 3
    </div>
    <div class="col">
      2 of 3
    </div>
    <div class="col">
      3 of 3
    </div>
  </div>
</div>
```
![](https://github.com/abhishekapk/Front-End-Hackathon-Resources/blob/master/Third%20Session/Assests/column.JPG)

```html
<div class="container">
  <div class="row">
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
  </div>
  <div class="row">
    <div class="col-8">col-8</div>
    <div class="col-4">col-4</div>
  </div>
</div>
```
![](https://github.com/abhishekapk/Front-End-Hackathon-Resources/blob/master/Third%20Session/Assests/column1.JPG)


For more details on Bootsrap, please visit - [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/)

#### References

* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
* [W3 Schools](https://www.w3schools.com/bootstrap4/bootstrap_get_started.asp)

#### Contributors 

* [Manyata](https://www.linkedin.com/in/manyata-hy-1jin/)
* [Srishti Gauraha](https://www.linkedin.com/in/srishti-gauraha-a2a8851a1/)
* [Smriti Halder](https://www.linkedin.com/in/srishti-gauraha-a2a8851a1/)
* [Abhishek Kumar Gupta](https://www.linkedin.com/in/abhishekapk) <a href="https://github.com/abhishekapk"><img src = "https://img.shields.io/badge/Follow-4183C4?logo=github&style=social"></a>