HTML Elements
The HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>


heading
HTML headings are titles or subtitles that you want to display on a webpage.

    <h1>Heading One</h1>
    <h2>Heading Two</h2>
    <h3>Heading Three</h3>
    <h4>Heading Four</h4>
    <h5>Heading Five</h5>
    <h6>Heading Six</h6>
    <h7>Heading Seven</h7>


paragraph
A paragraph always starts on a new line, and is usually a block of text.

<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt omnis dignissimos, sapiente itaque est soluta ad vitae quae commodi alias quod atque distinctio molestias, illo, officiis facilis quam? Reprehenderit, architecto.</p>





attributes
HTML attributes provide additional information about HTML elements.

<a href=""> </a>
<img src="img_girl.jpg" width="500" height="600">
<img src="img_girl.jpg" alt="Girl with a jacket">

Self Closing
<p>This is a <br> paragraph with a line break.</p>


html styles
The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>


<p>I am normal</p>
<p style="color:red;">I am red</p>
<p style="color:blue;">I am blue</p>
<p style="font-size:50px;">I am big</p>


html formatting
HTML contains several elements for defining text with a special meaning.

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text


list
HTML lists allow web developers to group a set of related items in lists.

<ul> − An unordered list. This will list items using plain bullets.

<ol> − An ordered list. This will use different schemes of numbers to list your items.

<dl> − A definition list. This arranges your items in the same way as they are arranged in a dictionary.

<ul>
         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
</ul>

      <ul type = "square">
         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
      </ul>

      <ul type = "circle">
         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
      </ul>

      <ul type = "disc">
         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
      </ul>

      <ol>
         <li>Beetroot</li>
         <li>Ginger</li>
         <li>Potato</li>
         <li>Radish</li>
      </ol>


tables
HTML tables allow web developers to arrange data into rows and columns.
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>


forms
The HTML <form> element is used to create an HTML form for user input:

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
  <input type="submit" value="Submit">
</form>


