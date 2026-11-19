# HTML
Hyper Text Markup Language
-> HTML is the code that is used to structure a web page and its content.
-> The component used to design the structure of websites are called HTML tags.
# First HTML file
-> HTML file Extention is : .html 
    Example : index.html
# HTML Tag
-> A container for some content or other HTML tags.
    ->  < start tag > Content < /End tag >
# Basic HTML Page
<!DOCTYPE html> // Tells browser you are using HTML5
<html> // Root of an html document
    <head> // Container for metadata
        <title>Title</title> Page title
    </head>
    <body> // Contains all data renderer by the browser
        <p>hello world</p> // Paragraph tag
    </body>
</html>
-> Html tag is parent of head & body tag.
-> Most of html elements have opening & closing tags with content in between
-> Some tags have no content in between, eg - <br>.
-> We can use inspect element/view page source to edit html.
# Comments in HTML
-> This is part of code that should not be parsed.
-> <!-- This is an HTML Comment -->
# HTML is NOT case sensitive
<p> = <P>
<html> = <HTML>
<head> = <HEAD>
<body> = <BODY>
# Basic HTML Tags
-> HTML Attributes : Attributes are used to add more information to the tag
    -> <html lang="en">
# Heading Tag
-> Used to display headings in HTML.
h1 (most important)
h2
h3
h4
h5
h6 (least important)
# Paragraph Tag
-> Used to add paragraphs in HTML.
    <p> This is a sample paragraph </p>
# Anchor Tag
-> Used to add links to your page.
    <a href="https://google.com"> Google </a>
# Image Tag
-> Used to add images to your page
    <img src="/image.png" alt="Random Image">
# Br Tag
-> Used to add next line(line breaks) to your page.
    <br>
# Bold, Italic & Underline Tags
-> Used to highlight text in your page
    <b> Bold </b>
    <i> Italic </i>
    <u> Underline </u>
# Big & Small Tags
-> Used to display big & small text on your page.
    <big> Big </big>
    <small> Small </small>
# Hr Tag
-> Used to display a horizontal ruler, used to separate content.
    <hr>
# Subscript & Superscript Tag
-> Used to display a horizontal ruler, used to separate content.
    <sub> subscript </sub>
    <sup> superscript </sup>
# Pre Tag
-> Used to display text as it is (without ignoring spaces & next line).
    <pre> This
        is a sample
        text.
    </pre>
# Page Layout Techniques
-> using Semantic tags for layout.
-> using the Right Tags
<header>
<main>
<footer>
# Inside Main Tag
-> Section Tag // For a section on your page
<section>
-> Article Tag // For an article on your page
<article>
-> Aside Tag // For content aside main content(ads)
<aside>
# Revisiting Anchor Tag
-> <a href="https://google.com" target="_main"> Google </a>
-> <a href="https://google.com"> <img src="link"> </a>
# Revisiting Image Tag
-> <img src="link" height=50px >
-> <img src="link" width=50px >
# Div Tag
-> Div is a container used for other HTML elements.
-> Block Element (takes full width).
# List : Div Tags
<address>   <article>   <aside> <blockquote>    <canvas>
<dd>    <div>   <dl>    <dt>    <fieldset>
<figcaption>    <figure>    <footer>    <form>
<h1>-<h6>   <header>    <hr>    <li>    <main>
<nav>   <noscript>  <ol>    <p> <pre>
<section>   <table> <tfoot> <ul>    <video>
# Span Tag
-> Span is also a container used for other HTML elements.
-> Inline Element (takes width as per size).
# List : Span Tags
<a> <abbr> <acronym> <b> <bdo> <bt> <button> <cite>
<code> <dfn> <em> <i> <img> <input> <kbd> <label> <map>
<object> <tt> <var> <output> <q> <samp> <script> <select>
<small> <span> <strong> <sub> <sup> <textarea> <time>
# List in HTML 
-> Lists are used to represent real life list data.
unordered               ordered
<ul>                    <ol>
<li>Apple</li>          <li>Apple</li>
<li>Mango</li>          <li>Mango</li>
</ul>                   </ol>
# Tables in HTML
-> Tables are used to represent real life table data.
<tr> // used to display table row
<td> // used to display table data
<th> // used to display table header
# Tables in HTML
<table>
    <tr>
        <th>Name</th>
        <th>Roll No</th>
    </tr>
    <tr>
        <td>Khasim</td>
        <td>060</td>
    </tr>
</table>
# Caption in Tables.
<caption> Student Data </caption>
# thead & tbody in Tables
<thead> // to wrap table head
<tbody> // to wrap table body
# colspan attribute
colspan="n"
-> used to create cells which spans over multiple columns.
# Form in HTML
-> Forms are used to collect data from the user.
-> Eg- sign up/login/help requests/contact me.
<form>
    form content.
</form>
# Action in Form.
-> Action attribute is used to define what action needs to be performed when a form is submitted.
<form action="/action.php" >
# Form Element : Input
<input type="text" placeholder="Enter Name">
# Label
<label for="id1">
    <input type="radio" value="class X" name="class" id="id1">
</label>
<label for="id2">
    <input type="radio" value="class X" name="class" id="id2">
</label>
# Class & Id
<div id="id1" class="group1">

</div>
<div id="id2"> class="group1">

</div>
# Checkbox
<label for="id1">
    <input type="checkbox" value="class X" name="class" id="id1">
</label>
<label for="id2">
    <input type="checkbox" value="class X" name="class" id="id2">
</label>
# Textarea
<textarea name="feedback" id="feedback" placeholder="Please add Feedback">
</textarea>
# Select
<select name="city" id="city"> 
    <option value="Delhi"> Delhi </option>
    <option value="Mumbai"> Delhi </option>
    <option value="Banglore"> Delhi </option>
</select>
# iframe Tag
-> website inside website
<iframe src="link"> Link </option>
# Video Tag
-> <video src="myVid.mp4"> My Video </video>
Attributes :
- controls
- height
- width
- loop
- autoplay
