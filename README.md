Download Link: https://assignmentchef.com/product/solved-web222-assignment3-writing-html-containers
<br>
Objective:

Practice writing HTML Containers / Media Elements, Updating the DOM with data

Specification:

Update HTML &amp; JavaScript code for each of the following pages according to the instructions outlined below. To begin, download the assignment3.zip file containing all of the files required for Assignment 3 from blackboard.

Uncompress the zip files somewhere on your local machine. When you’re ready to begin editing the files, open the uncompressed folder (assignment3) in Visual Studio Code (https://code.visualstudio.com) using “Open Folder”. You may test your html files in any modern browser (Chrome, Firefox, Safari, Internet Explorer, etc).

“Assignment 3 Home” – index.html:

Update the “Assignment 3 Home” page with the following:

<ol>

 <li>Add a <strong>professional greeting </strong>to the visitor, i.e.: “Welcome to my website, I will be demonstrating HTML5 principles and techniques, DOM manipulation”… and so on.</li>

 <li>Add a relevant <strong>header </strong>as a title for the next section (step 3)</li>

 <li>Add a <strong>short paragraph </strong>that introduces this website, i.e.: “This site contains 8 pages, including: Home, HTML Text, HTML Lists”… and so on. <strong>NOTE: </strong>This paragraph <strong>must include all relevant links</strong> to the <strong>8 pages .</strong></li>

 <li>Add a relevant <strong>header </strong>as a title for the next section (step 5)</li>

 <li>Add a <strong>short paragraph </strong>introducing HTML 5, i.e.: “This site utilizes HTML5: a markup language used for structuring and presenting content on the World Wide Web”… and so on.</li>

</ol>

“HTML Lists” – list.html:

Update the “HTML Lists” page with the following:

<ol>

 <li>Inside list.html, create any <strong>nested list </strong>with meaningful items using countries, provinces and cities.</li>

</ol>

<ul>

 <li>The nested list should contain at least <strong>one ordered list </strong>and at least <strong>one unordered list. </strong></li>

</ul>

<ol start="2">

 <li>Update the list.html page to include two containers (i.e.: &lt;div&gt;) with unique id values</li>

 <li>Add a relevant <strong>header </strong>as a title for the next section (step 4)</li>

 <li>Use the <strong>fruits </strong>array inside the <strong>js </strong>file (js/list.js) to write (using JavaScript) an ordered list containing all the fruit inside the array, (ie:”Apples”,”Oranges”,”Pears”,”Grapes”,”Pineapples”,”Mangos”) to one of your containers in the list.html page. Be sure to write to your container (using JavaScript) <strong>after </strong>the window has completely loaded. The ordered list should look like the image below when complete:</li>

 <li>Add a relevant <strong>header </strong>as a title for the next section (step 6)</li>

 <li>Use the <strong>directory </strong>array inside the <strong>js </strong>file (js/list.js) to write (using JavaScript) a nested unordered list containing all the files and directories (with their files) inside the array to one of your containers in the list.html page.</li>

</ol>

You will notice that files have the type “<strong>file</strong>” and consist of a “<strong>name</strong>” property, whereas directories have the type “<strong>directory</strong>” and consist of a “<strong>name</strong>” property in addition to an <strong>array of files</strong>. Use these properties to correctly construct your nested unordered list (using JavaScript).

Be sure to write to your container <strong>after </strong>the window has completely loaded (using JavaScript). The nested  unordered list should look like the image below when complete:

“HTML Tables” – table.html:

Update the “HTML Tables” page with the following:

<ol>

 <li>Inside table.html, create the following two tables, each with a relevant <strong>header </strong>as a title:</li>

</ol>




<ul>

 <li>The <strong>1st table </strong>should be composed of the elements: <strong>&lt;table</strong> <strong>style=”border:1px solid;”&gt;</strong>, <strong>&lt;tr&gt;</strong>, <strong>&lt;th&gt;</strong>, <strong>&lt;td&gt; </strong>and <strong>&lt;caption&gt; </strong>with meaningful table contents, i.e.: a table of your hobbies, description and time spent etc.</li>

 <li>The <strong>2nd table </strong>should be composed of the elements: <strong>&lt;table style=”border:1px solid;”&gt;</strong>, <strong>&lt;tr&gt;</strong>, <strong>&lt;th&gt;</strong>, <strong>&lt;td&gt;</strong>, <strong>&lt;thead&gt;</strong>, <strong>&lt;tfoot&gt; </strong>and <strong>&lt;tbody&gt; </strong>with meaningful table contents, i.e.: a table of your favourite personalities, authors, descriptions etc.</li>

</ul>

<ol start="2">

 <li><strong>Update the table.html page to include an additional container (i.e.: &lt;div&gt;) with a unique id value. </strong></li>

 <li>Add a relevant <strong>header </strong>as a title for the next section (step 4)</li>

 <li>Use the <strong>users </strong>array inside the <strong>js </strong>file (js/table.js) to write a complete <strong>3rd table </strong>containing all the users inside the array (and an appropriate header row), to your container in the table.html page.</li>

</ol>




You will notice that users consist of the properties: <strong>first_name</strong>, <strong>last_name</strong>, <strong>age</strong>, and <strong>email</strong>. Use these properties to correctly construct your table (using JavaScript) with the following headers: <strong>First Name</strong>, <strong>Last Name</strong>, <strong>Age </strong>and <strong>Email</strong>. You must also ensure that all email addresses are rendered as a valid “mailto” link and will open as a new message in the user’s default mail client when clicked.

Be sure to write to your container <strong>after </strong>the window has completely loaded. The table should look like the image below when complete:

“HTML Images” – image.html:

Update the “HTML Images” page with the following:

<ol>

 <li>Find the given image with the file named <strong>png </strong>under the “<strong>img</strong>” sub-folder included in the zip file. Show the image in your web page using a relative path. Ensure that when the image is not available, the text “<strong>ICT School, Seneca College</strong>” is visible on the page and make the image a <strong>hyperlink to the ICT School website</strong>.</li>

 <li><strong>Update the image.html page to include an additional container (i.e.: &lt;div&gt;) with a unique id value. </strong></li>

 <li>Add a relevant <strong>header </strong>as a title for the next section (step 4)</li>

 <li>Use the <strong>images </strong>array inside the <strong>js </strong>file (js/image.js) to write 5 new <strong>&lt;figure&gt; </strong>elements to your container in the image.html page (using JavaScript). You will notice that each image in the array has the following properties: <strong>caption</strong>, <strong>alt </strong>and <strong>url</strong>. Use these properties to correctly construct (using JavaScript) your <strong>&lt;figure&gt; </strong>elements such that each element contains a valid <strong>image </strong>(using <strong>url </strong>and <strong>alt) </strong>as well as a <strong>caption </strong>underneath the image with the message contained within the <strong>caption </strong>property</li>

</ol>

Be sure to write to your container <strong>after </strong>the window has completely loaded (using JavaScript). The <strong>&lt;figure&gt; </strong>elements should look like the image below when complete (only the first 2 shown):

“HTML5 Audio” – audio.html:

Update the “HTML5 Audio” page with the following:

<ol>

 <li>Update the audio.html page to include an additional container (i.e.: &lt;div&gt;) with a unique id value.</li>

 <li>Use the <strong>audio </strong>object inside the <strong>js </strong>file (js/audio.js) to render an audio player in your container within the audio.html page.</li>

</ol>

You will notice that the audio object consists of the properties: <strong>controls </strong>and <strong>source</strong>. Use these properties to correctly construct (using JavaScript) your audio player with (or without) controls, and the correct source options.

Be sure to write to your container <strong>after </strong>the window has completely loaded.

“HTML5 Video” – video.html:

Update the “HTML5 Video” page with the following:

<ol>

 <li><strong>Update the video.html page to include an additional container (i.e.: &lt;div&gt;) with a unique id value. </strong></li>

 <li>Use the <strong>video </strong>object inside the <strong>js </strong>file (js/video.js) to render a video player in your container within the video.html page.</li>

</ol>

You will notice that the video object consists of the properties: <strong>controls</strong>, <strong>width</strong>, <strong>height </strong>and <strong>source</strong>. Use these properties to correctly construct (using JavaScript) your video player with (or without) controls, in the correct dimensions and using the correct source options.

Be sure to write to your container <strong>after </strong>the window has completely loaded.

“Seneca College” – seneca.html:

Update the “Seneca College” page with the following:

Find an image representing Seneca from the <strong>http://www.senecacollege.ca </strong>website.

Without downloading this image file, show the image in your web page (i.e.: use an absolute link to the file) – <strong>HINT: </strong>Right-click on the image and choose “<strong>inspect</strong>” – this will take you directly to the html responsible for rendering this image and you can see the relative path to its location on the server. Generate your <strong>absolute path </strong>using this as a starting point.  (E.g. The url may be something like this <a href="http://www.senecacollege.ca/shared/images/Seneca-50-BIM.svg">http://www.senecacollege.ca/shared/images/Seneca</a><a href="http://www.senecacollege.ca/shared/images/Seneca-50-BIM.svg">–</a><a href="http://www.senecacollege.ca/shared/images/Seneca-50-BIM.svg">50</a><a href="http://www.senecacollege.ca/shared/images/Seneca-50-BIM.svg">–</a><a href="http://www.senecacollege.ca/shared/images/Seneca-50-BIM.svg">BIM.svg</a> )

Ensure that when the image is not available, the text “<strong>Seneca College</strong>” is visible on the page.

Lastly, define three clickable areas on the image (three equal rectangle shapes from left to right is preferred) and make/map the areas hyperlinked to Seneca’s home website, ICT website and library website respectively.

“Honesty Statement” – honesty.html:

Update the “Honesty Statement” page with the following:

<ol>

 <li>Add date and your name in the provided places to complete the academic honesty declaration.</li>

</ol>

Other Requirements

<ul>

 <li>All tags/attributes must be in <strong>lower case. </strong></li>

 <li>Make sure to <strong>update the title </strong>with relevant text on <strong>each of the pages. Each page footer must have your full name as Student name (zero will be assigned if you do not write your name) </strong></li>

 <li>All of your html files <strong>MUST not contain any errors </strong>when tested using the W3C Markup Validation Service:</li>

</ul>








