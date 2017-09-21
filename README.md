<!DOCTYPE HTML>
<html>
  <head>Web Intro NOTES
    <title>"Project #1"</title>
  </head>
    <body>
      <H1>Intoduction to the Web</H1>
<em>The web is broken down into 3 basic components:</em><br>
<p><b>(1)</b> Client (my computer and browser)<br>
  <b>(2)</b> The Internet (web of routers)<br>
  <b>(3)</b> Servers (computer in a closet somewhere)</p>

Webpages are coded and read in HTML
(HyperText Markup Language). Servers hold the data
to be displayed on the brower. The server and brower
are able to interact with each other by using HTTP
(HyperText Transfer Protocol).</span><br><br>

<H2>HTML Basics</H2>
  HTML = HyperText Markup Language. HTML renders like
  normal text in the browser. We can edit the text by
  adding opening and closing <b>tags</b> around text.<br><br>
  <font size="-1">e.g. <b>< b> bolded text </ b> </b><br>
  e.g. <em>< em> italicized text </ em> </em><br>
  **note that tags above should not have spaces within <>
  </font><br><br>

This is an <b>opening tag</b>: < a><br>
This is a <b>closing tag</b>: </ a><br>
The entire tag is an <b>element</b>: <em>< a>text </ a> </em><br><br>

<H2>HTML Attributes</H2>
  Some HTML tags can accept <b>attributes</b>; additional terms
  that provide clarifying information for the browser.<br><br>
  For example:<br>
  <font size="-1"><em>< a href="insert url here">hyperlink display
  </ a></em> allows us to add a <a href="https://www.computerhope.com/jargon/h/hyperlin.htm">
  hyperlink</a> to text.<br>
  <em> < img src="image url" alt="text to display on error"></em>
  allows us to add an image inline with text.</font><br><br>

<img src="https://i.pinimg.com/736x/98/2b/fd/982bfdea8625901990337c51009a1cff--workout-tips-workout-gear.jpg">
<br><br>

To insert a link or image, the reference URL can be either a
<em>local destination</em> on your computer or a <em>http link</em>
on the web. In the examples above, "href" and "src" are
the <b>attributes</b>. If the image fails to load using the
< img> tag, then the defined "text" will appear. <br><br>

<H2>Other HTML Notes</H2>
  <b>Whitespace</b>: more than one space between text will not show up
  in HTML. In order to break a line onto a new section we must
  use a tag:<br><br>
  (1) < br> <b>break tag</b>, forces tag to next line.
  Break is a <em>void</em> tag, meaning it does not require
  a closing tag.<br>
  (2) < p>text</ p> <b>paragraph tag</b>,
  blocks text into a paragraph. The paragraph tag is a
  "box" <b>container element</b> because it blocks off a
  section of text from the preceding lines.<br><br>

Container elements can be either "inline" or "box":<br><br>

< div>text here</ div> is an example of "box" containter element.<br>
< span>text here</ span> is an example of "inline" container element.<br><br>

<b>Proper formatting</b>: HTML documents require proper formatting to display
   in a webpage. This including identifying the document type, header,
   title, body, and so on. See this code for proper formatting.<br><br>
   All of the text that is displayed on the webpage goes in the body.
   The head will contain metadata and CSS to style the page.
   The title will appear in the name of the tab. <br><br><br>
 </body>
</html>

