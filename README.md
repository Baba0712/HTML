HTML stands for Hypertext Markup Language.

Hypertext Markup Language or HTML is a markup language which is used to create website templates or WebPages to present the content on the World Wide Web. HTML pages are saved by adding .html or .html in web page name.

The basic structure of the HTML template is:
<html>
    <head>
          <title></title>
    </head>
     <body>
     </body>
</html>

=========================================================================

What Is The Difference Between HTML Elements And Tags?
Answer.
HTML elements communicate to the Browser how to represent the text. They become HTML tags when enclosed within angular brackets <>.

=========================================================================
What are tags?

A tag instructs the Browser about how to format the HTML properly. When you write an HTML page, you enter tags for many reasons to change the appearance of text, to show a graphic, or to make a link to another page. HTML uses symbols like “<” and “>” to enclose the tags. And symbol “\” for closing the tag.

Content is placed in between HTML tags in order to properly format it. It makes use of the less than symbol (<) and the greater than symbol (>). A slash symbol is also used as a closing tag. 
		For example: <strong>sample</strong>
		
An HTML tag is commonly defined as a set of characters constituting a formatted command for a Web page. At the core of HTML, tags provide the directions or recipes for the visual content that one sees on the Web
=========================================================================
Do all HTML tags come in a pair?
		No, there are single HTML tags that do not need a closing tag. Examples are the <img> tag and <br> tags.

=========================================================================
Do all character entities display properly on all systems?
		No, there are some character entities that cannot be displayed when the operating system that the browser is running on does not support the characters. When that happens, these characters are displayed as boxes.
=========================================================================
What is an image map?

Image map lets you link to many different web pages using a single image. You can define shapes in images that you want to make part of an image mapping.
=========================================================================
What is the advantage of collapsing white space?

White spaces are a blank sequence of space characters, which is treated as a single space character in HTML. Because the browser collapses multiple spaces into a single space, you can indent lines of text without worrying about multiple spaces. This enables you to organize the HTML code into a much more readable format.
=========================================================================
Can attribute values be set to anything or are there specific values that they accept?

Some attribute values can be set to only predefined values. Other attributes can accept any numerical value that represents the number of pixels for a size.
=========================================================================
How do you create links to sections within the same page?

Links can be created using the <a> tag, with referencing through the use of the number (#) symbol. For example, you can have one line as <a href=”#topmost”>BACK TO TOP</a>, which would result in the words “BACK TO TOP” appearing on the webpage and links to a bookmark named topmost. You then create a separate tag command like <a name=”topmost”> somewhere on the top of the same webpage so that the user will be linked to that spot when he clicked on “BACK TO TOP”.
=========================================================================
Is there any way to keep list elements straight in an HTML file?

By using indents, you can keep the list elements straight. If you indent each subnested list in further than the parent list that contains it, you can at a glance determine the various lists and the elements that it contains.

=========================================================================
What is the use of alternative text in image mapping?

When you use image maps, it can easily become confusing and difficult to determine which hotspots correspond to which links. Using alternative text lets, you put a descriptive text on each hotspot link.
=========================================================================
Do older HTML files work on newer browsers?

Yes, older HTML files are compliant to the HTML standard. Most older files work on the newer browsers, though some features may not work.
=========================================================================
Does a hyperlink apply to text only?

No, hyperlinks can be used in the text as well as images. That means you can convert an image into a link that will allow users to link to another page when clicked. Surround the image within the <a href=” “>…</a> tag combinations.
=========================================================================
If the user’s operating system does not support the needed character, how can the symbol be represented?

In cases wherein their operating system does not support a particular character, it is still possible to display that character by showing it as an image instead.
=========================================================================
How do you change the number type in the middle of a list?

The <li> tag includes two attributes – type and value. The type attribute can be used to change the numbering type for any list item. The value attribute can change the number index.
=========================================================================
What are style sheets?

Style sheets enable you to build consistent, transportable, and well-defined style templates. These templates can be linked to several different web pages, making it easy to maintain and change the look and feel of all the web pages within site.
=========================================================================
What is the advantage of grouping several checkboxes together?

Although checkboxes don’t affect one another, grouping checkboxes together help to organize them. Checkbox buttons can have their name and do not need to belong to a group. A single web page can have many different groups of checkboxes.
=========================================================================
What will happen if you overlap sets of tags?

If two sets of HTML tags are overlapped, only the first tag will be recognized. You will find this problem when the text does not display properly on the browser screen.
=========================================================================
What are applets?

Applets are small programs that can be embedded within web pages to perform some specific functionality, such as computations, animations, and information processing. Applets are written using the Java language.
=========================================================================
What if there is no text between the tags or if a text was omitted by mistake? Will it affect the display of the HTML file?

If there is no text between the tags, then there is nothing to format. Therefore no formatting will appear. Some tags, especially tags without a closing tag like the <img> tag, do not require any text between them.
=========================================================================
Is it possible to set specific colors for table borders?

You can specify a border color using style sheets, but the colors for a table that does not use style sheets will be the same as the text color.
=========================================================================
How do you create a link that will connect to another web page when clicked?

To create hyperlinks, or links that connect to another web page, use the href tag. The general format for this is: 
<a href=”site”>text</a>
Replace “site” with the actual page URL that is supposed to be linked to when the text is clicked.
=========================================================================
What other ways can be used to align images and wrap text?

Tables can be used to position text and images. Another useful way to wrap text around an image is to use style sheets.
=========================================================================
Can a single text link point to two different web pages?

No. The <a> tag can accept only a single href attribute, and it can point to only a single web page.
=========================================================================
What is the difference between the directory and menu lists and the unordered list?

The key difference is that the directory and menu lists do not include attributes for changing the bullet style.
=========================================================================
 Can you change the color of bullets?

The bullet color is always the same as that of the first character in the list item. If you surround the <li> and the first character with a set of <font> tags with the color attribute set, the bullet color, and the first character will be a different color from the text.
=========================================================================
What are the limits of the text field size?

The default size for a text field is around 13 characters. However, if you include the size attribute, you can set the size value to be as low as 1. The maximum size value will be determined by the browser width. If the size attribute is set to 0, the size will be set to the default size of 13 characters.
=========================================================================
Do <th> tags always need to come at the start of a row or column?

Any <tr> tag can be changed to a <th> tag. This causes the text contained within the <th> tag to be displayed as bold in the browser. Although <th> tags are mainly used for headings, they do not need to be used exclusively for headings.
=========================================================================
What is the relationship between the border and rule attributes?

Default cell borders, with a thickness of 1 pixel, are automatically added between cells if the border attribute is set to a nonzero value. Likewise, If the border attribute is not included, a default 1-pixel border appears if the rules attribute is added to the <table> tag.
=========================================================================
What is a marquee?

A marquee allows you to put a scrolling text in a web page. To do this, place whatever text you want to appear scrolling within the <marquee> and </marquee> tags.
=========================================================================
How do you create text on a webpage that will allow you to send an email when clicked?

To change text into a clickable link to send email, use the mailto command within the href tag. The format is as follows:
<A HREF=”mailto:youremailaddress”>text to be clicked</A>
=========================================================================
Are <br> tags the only way to separate sections of text?

No. The <br> tag is only one way to separate lines of text. Other tags, like the <p> tag and <blockquote> tag, also separate sections of text.
=========================================================================
Are there instances where the text will appear outside of the browser?

By default, the text is wrapped to appear within the browser window. However, if the text is part of a table cell with a defined width, the text could extend beyond the browser window.
=========================================================================
How are active links different from normal links?

The default color for normal and active links is blue. Some browsers recognize an active link when the mouse cursor is placed over that link; others recognize active links when the link has the focus. Those that don’t have a mouse cursor over that link is considered a normal link.
=========================================================================
Do style sheets limit the number of new style definitions that can be included within the brackets?

Style sheets do not limit the number of style definitions that can be included within the brackets for a given selector. Every new style definition, however, must be separated from the others by a semicolon symbol.
=========================================================================
Can I specify fractional weight values such as 670 or 973 for font weight?

Implementation largely depends on the browser, but the standard does not support fractional weight values. Acceptable values must end with two zeroes.
=========================================================================
What is the hierarchy that is being followed when it comes to style sheets?

If a single selector includes three different style definitions, the definition that is closest to the actual tag takes precedence. Inline style takes priority over embedded style sheets, which takes priority over external style sheets.
=========================================================================
Can several selectors with class names be grouped together?

You can define several selectors with the same style definition by separating them with commas. This same technique also works for selectors with class names.
=========================================================================
What happens if you open the external CSS file in a browser?

When you try to open the external CSS file in a browser, the browser cannot open the file, because the file has a different extension. The only way to use an external CSS file is to reference it using <link/> tag within another HTML document.
=========================================================================
How do you make a picture into a background image of a web page?

To do this, place a tag code after the </head> tag as follows:<body background = “image.gif”>

Replace image.gif with the name of your image file. This will take the picture and make it the background image of your web page.
=========================================================================
What happens if the list-style-type property is used on a non-list element like a paragraph?

If the list-style-type property is used on a non-list element like a paragraph, the property will be ignored and do not affect the paragraph.
=========================================================================
When is it appropriate to use frames?

Frames can make navigating a site much easier. If the main links to the site are located in a frame that appears at the top or along the edge of the browser, the content for those links can be displayed in the remainder of the browser window.
=========================================================================
What happens if the number of values in the rows or cols attribute doesn’t add up to 100 percent?

The browser sizes the frames relative to the total sum of the values. If the cols attribute is set to 100%, 200% the browser displays two vertical frames with the second being twice as big as the first.
=========================================================================
Which browsers support HTML5?

The latest versions of Google Chrome, Apple Safari, Mozilla Firefox, and Opera all support most of the HTML5 features.
=========================================================================
Name two new tags included in the HTML 5

<Video> and <Audio> are new tags which are included in HTML5 version. They are mainly used as a replacement for Flash, Silverlight, and similar technologies to play multimedia items.
=========================================================================
What is <figure> in HTML5?

This tag represents a piece of self-contained flow content. It is mostly used as a single unit as a reference the main flow of the document.
=========================================================================
What is the use of Canvas element?

The canvas element helps to build charts, graphs, bypass Photoshop to create 2D images and place them directly into HTML5 code.

=========================================================================
Tell me two benefits of HTML5 Web Storage

Two main benefits of HTML5 Web Storage:

It can store up to 10 MB data which is certainly more than what cookies have.
Web storage data cannot be transferred with the HTTP request. It helps to increase the performance of the application.
=========================================================================
What are two types of Web Storage in HTML5?

	Two storage types of HTML5 are:

	Session Storage:
	It stores data of current session only. It means that the data stored in session storage clear automatically when the browser is closed.

	Local Storage:
	Local storage is another type of HTML5 Web Storage. In local storage, data is not deleted automatically when the current browser window is closed.
=========================================================================
What is the Application Cache in HTML5 and why it is used?

	The Application Cache concept means that a web application is cached. It can be accessible without the need for internet connection.

	Some advantages of Application Cache:

	*Offline browsing – Web users can also use the application when they are offline.
	*Speed – Cached resources load quicker
	*Reduce the server load – The web browser will only download updated resources from the server.
=========================================================================
Explain five new input types provided by HTML5 for forms?

		Following are the important, new data types offered by HTML5:

		Date: It allows the user to select a date.
		datetime-local: This input type allows the user to select a date and time without time zone.
		datetime: This input type allows the user to select a date and time with time zone.
		month: It enables the user to select a month and year
		email: These input fields used to contain an e-mail address.
=========================================================================
HTML5 is the latest or updated version of markup language that defines HTML.
Some new features in HTML5 include:
		* DOCTYPE declaration – <!DOCTYPE html>
		
		* section – Section tag defines a section in the document, such as a header, footer or in other sections of the document. It is used to define the structure of the document. <section></section>
		
		*header – Header tag defines the head section of the document. A header section always sticks at the top of the document. <header></header>
		
		*footer – Footer tag defines the footer section of the document. A footer section always sticks at the bottom of the document. <footer></footer>
		
		*article – Article tag defines an independent piece of the content of a document. <article> </article>
		
		*main – The main tag defines the main section in the document which contains the main content of the document. <main></main>
		
		*figcaption – Figcaption tag defines the caption for the media element such as an image or video. <figcaption></figcaption>

=========================================================================
What Are The New Features Introduced In HTML5?
Answer.
HTML5 introduces a number of new elements and attributes that help in building an attractive webSite, that we see nowadays.

It supports following new features.

		* New Semantic Elements – These are like <header>, <footer>, and <section>.
		* Forms 2.0 – It contains improvements to HTML web forms. It has introduced new attributes for the <input>   tag.
		* Persistent Local Storage – With HTML5, it is possible to achieve this, without resorting to third-party plugins.
		* WebSocket – It facilitates setting up a bidirectional communication for web applications.
		* Server-Sent Events(SSE) – These events got introduced in HTML5. The direction of the flow of the execution of these events is from the server to the Web Browser.
		* Canvas – It supports a two-dimensional drawing surface that is programmable using JavaScript.
		* Audio & Video – It allows embedding audio or video on the web pages without resorting to third-party plugins.
		* Geolocation – It facilitates the visitors to share their physical location with the web application.
		* Microdata – It allows building our personal vocabulary beyond HTML5 and extends our web pages with those custom semantics.
		* Drag and drop – It supports to Drag and drop the items from one location to another location on the same Web page.

=========================================================================

Anchor tag in HTML is used for linking between two sections or two different web pages or website templates.
To open an url into a new tab in the browser upon a click, we need to add target attribute equal to _blank.
<a href=”#” target=”_blank”></a>

=========================================================================
Write an HTML code to form a table to show the below values in a tabular form with heading as Roll No., Student name, Subject Name, and values as
1, Ram, Physics
2, Shyam, Math
3, Murli, Chemistry
Ans: To represent the above values in an HTML table format, the code will be:
			<!DOCTYPE html>
			<html>
				<head>
					<style>
					table, th, td {
					border: 1px solid black;
					}
					</style>
				</head>
				<body>
					<table >
						<tr>
						<th> Roll No. </th>
						<th> Student Name </th>
						<th> Subject Name </th>
						</tr>
							<tr>
							<td> 1 </td>
							<td>Ram</td>
							<td> Physics </td>
							</tr>
							<tr>
							<td> 2 </td>
							<td> Shyam </td>
							<td> Math </td>
							</tr>
							<tr>
							<td> 3 </td>
							<td> Murli </td>
							<td> Chemistry </td>
							</tr>
					</table>
				</body>
			</html>
			
=========================================================================
			
Semantic elements are HTML elements which represent its meaning to the browser and developer about its contents.
For Example – p tag represents a paragraph, a tag represents anchor tag, form tag, table tag, article tag and many more are semantic elements in HTML. Whereas div tag, span tag, bold tag are not semantic elements.

=========================================================================

	Define attributes in HTML tag.
Ans: The HTML tag contains a field inside their tag which is called attributes of that tag.
For Example:
			<img src=”#”> here in this tag src is img tag attributes.
			<input type=”text”> here in this tag type is input tag attributes.
=========================================================================
			
	Can we modify the attribute’s value of the HTML tag dynamically?
Ans: Yes, we can modify the value of the attributes by using JavaScript.
		Below is the input element whose attribute will be modified from text to password, JS code to modify the attribute value:
						<input type=“text” id=“inputField”>
						document.getElementById(“inputField”).attr(“type”, “password”);
						
=========================================================================

Comments are used by developers to keep a track of the code functionality and also help the other developers in understanding the code functionalities easily.
The commented out lines will not be shown in the browser. To comment a line, the line should start by this <!– and end by this –>. Comments can be of one line or of multiple lines.
		For Example:
				<!-- This is one line comment -->
				<!-- This is multiple
						line of two or
						more line -->
=========================================================================

What are inline elements and block-level elements in HTML?
Ans: 
		Block elements are the blocks that take the full available width and always start from a new line. It will stretch itself to the full available width of the available container width. Block level elements are <div>, <p>, <img>, <section> and many more.
		
		Inline elements are the elements that will only take the width that is required to fit into the container.
		
		For Example, take the flow of text on the page. When the line of the text takes the full width of the container it wraps itself into a new line and again goes in the same way.
		
		Whereas the inline element will take only that much space or width that it is needed for them. Inline elements are <span>, <label>, <a>, <b> and many more.
		
=========================================================================
		
		Can we change inline elements into block-level elements?
Ans: Yes, we can change inline elements into block-level elements by adding display equal to block in its CSS tag. Writing it will change the inline elements into block elements and then inline elements will also take the full width of the container.
						display: block;
						
=========================================================================						

<br> tags are used to enter a new line into the HTML contents. These tags are generally used to separate two different lines of text between each other.

=========================================================================

The common structure which all html pages follow are:
	(i) DOCTYPE – It is a special tag in html which is always written at the top of the html document, i.e. at the start of the html template. DOCTYPE is used to convey to the browser about the HTML version.
					<!DOCTYPE html>
	(ii) HTML – After DOCTYPE tag, html tag is written to start the html template. All the html code will be placed into this html tag. It works as the container for the whole html page elements.
		<html>
					<!-- Rest of the html code will come inside it -->
		</html>
	(iii) HEAD – <head> tag is the first element inside the <html> tag. It is used to provide information to the browser about the page and its contents.
		Search Engine Optimization (SEO) techniques are written inside this tag. <title>, <meta> tags are written inside these tag. CSS and JS external links or internal CSS and JS are also written inside this tag.
					<head>
							   <meta charset="UTF-8">
						   <meta name="viewport" content="width=device-width, initial-scale = 1.0">
						   <title>HTML Interview Questions</title>
					</head>
	(iv) BODY – <body> tag are written after the closing tag of the <head> tag, i.e. after </head>. Whatever html code is written inside these tags will be shown by the browser as website content.
			<body>
					   <h2>Top HTML Interview Questions</h2>
					   <p>HTML stands for Hypertext Markup Language</p>
			</body>
			All together the whole body will be:
			<! DOCTYPE html>
			<html>
					   <head>
								  <meta charset="UTF-8">
								 <meta name="viewport" content="width=device-width, initial-scale = 1.0">
								 <title>HTML Interview Questions</title>
								 <style type="text/css">
											<!-- CSS Code will be written into these -->
											h2 {
													  color: #1855b5;
												}
										   p   {
													 color: #3bd256;
													 font-weight: 600;
										       }
							  </style>
							  <script type="text/javascript">
										  <!-- Javascript code will be written into these -->
							  </script>
				</head>
				 <body>
							<h2>Top HTML Interview Questions</h2>
							<p>HTML stands for Hypertext Markup Language</p>
				</body>
			</html>
=========================================================================
			
Meta tags in html are used by the developer to tell the browser about the page description, author of the template, character set, keywords and many more.
Meta tags are used for search engine optimization to tell the search engine about the page contents.
			<meta charset="UTF-8">
			<meta name="viewport" content="width=device-width, initial-scale = 1.0">
			<meta name="description" content="HTML interview questions">
			<meta name="author" content="Author Name">
			<meta name="copyright" content="All Rights Reserved">

=========================================================================			
The list elements in HTML are:
			Ordered List (<ol>) – An Ordered List or ol tag are the list which will list the items in an ordered 	way, i.e. numbered or alphabetically.
			Unordered List (<ul>) – An Unordered List or ul tag is the list which will list the items in an unordered way, i.e. in bulleted format or in any other format.
			Definition List (<dl>) – A definition List or dl tag arranges the items in the way in which they are arranged in a dictionary.
			
Ordered List:
<!DOCTYPE html>
                <html>
					   <head>
							 <title>HTML Interview Questions Ordered List</title>
					   
								<style>
								h1{
									   color: red;
								}
								li{
									   color: #0070ff;
								} 
							   </style>
						</head>
					 <body>
						<h1>Ordered List : </h1>
						  <ol>
								 <li>HTML</li>
								 <li>CSS</li>
								 <li>Bootstrap</li>
								 <li>JavaScript</li>
						 </ol>
					</body>
               </html>
Output:
		ordered-list :
		1.HTML
		2.CSS
		3.Bootstrap
		4.JavaScript
		
		
Unordered List:
		<!DOCTYPE html>
                     <html>
						<head>
							<title>HTML Interview Questions Unordered List</title>
							<style>
									 h1{
											 color: red;
									 }
									 li{
											 color: #0070ff;
									} 
							</style>
					   </head>
						<body>
								<h1>Unordered List : </h1>
										<ul>
												 <li>HTML</li>
												 <li>CSS</li>
												 <li>Bootstrap</li>
												 <li>JavaScript</li>
										</ul>
						</body>
					</html>
Output:
		Unordered-list :
			*HTML
			*CSS
			*Bootstrap
			*JavaScript
			
			
Definition List:
			<!DOCTYPE html>
					<html>
						<head>
								<title>HTML Interview Question Definition List</title>
						        <style>
										 dt {
											 font-weight: 600;
											 font-size: 25px;
											 color: red;
											 }
										dd {
											font-weight: 500;
											font-size: 15px;
											color: #0070ff;
											}
						        </style>
						</head>
						<body>
							   <dl>
									<dt><strong>HTML</strong></dt>
											<dd>HTML stands for Hypertext Markup Language</dd>
									<dt><bold>CSS</bold></dt>
											<dd>CSS stands for Cascading Style Sheets</dd>
							  </dl>
					    </body>
					</html>


=========================================================================
What are some of the common lists that can be used when designing a page?
	You can insert any or a combination of the following list types:
		– ordered list
		– unordered list
		– definition list
		– menu list
		– directory list
Each of this list types makes use of a different tag set to compose

=========================================================================
Iframe tag is written as <iframe>.

An iframe is used to display different document content inside the different document content in a rectangular region in the browser. When different document content is embedded into a current HTML content, then it is known as an inline iframe.

The src attribute contains the path to the document that occupies the inline iframe.

	<!DOCTYPE html>
           <html>
                       <head>
                               <title>HTML Interview Questions Iframes</title>
                      </head>
                      <body>
                                  <p>Iframe HTML Code</p>
                                 <iframe src = "demo_iframe.htm" width = "300" height = "300">
                                            Sorry your browser does not support inline frames.
                                 </iframe>
                     </body>
         </html>
		 
=========================================================================

Forms in html are required when we want to collect the user information whenever a user fills any form or provides any details and when we want to save it into our database.

		<!DOCTYPE html>
                      <html>

                             <head>
                                         <title>HTML Interview Question Form tag</title>
										  <style>
											  form {
														 width: 200px;
														 border: 2px solid blue;
														 margin: 0 auto;
														 padding: 60px 100px;
													  }
										      p {
													  color: red;
													  font-size: 16px;
													  font-weight: 600;

													}
											input::placeholder{
																color: blue;
															  }
											 button {
														line-height: 20px;
														text-align: center;
														background: green;
														border: 0;
														color: #ffffff;
													    font-size: 14px;
													    padding: 15px 64px;
													    margin-top: 20px;
													  }

											</style>
                             </head>
                             <body>
                                    <form >
									   <p>Name:</p>
											<input type = "text" name = "user_name" placeholder = "Enter Name"/>
										<br/>
										<br/>
										<p>Email: </p>
											<input type = "email" name = "user_email" placeholder = "Enter email"/>
											<br/>
										<br/>
                                        <p>Password: </p>
											<input type="password" name = "user_pwd" placeholder = "Enter Password" />
											<br/>
										<button> Submit </button>
                                    </form>
                                </body>
                        </html>
=========================================================================

A heading is a block level element which is used to give a heading to the particular section or topic.

A total of 6 types of headings can be written in HTML:

<!DOCTYPE html>
<html>
	<head>
		<style>
		h1{
				   color: red;
			}
		h2{
				   color: blue;
			}
		h3{
				   color : green;
			}
		h4{
				   color: purple;
			}
		h5{
				   color: yellow;
			}
		h6{
				   color: orange;
			}
		</style>
	</head>
	<body>
		<h1>Heading 1</h1>
		<h2>Heading 2</h2>
		<h3>Heading 3</h3>
		<h4>Heading 4</h4>
		<h5>Heading 5</h5>
		<h6>Heading 6</h6>
	</body>
</html>

=========================================================================

How can we create a hyperlink in HTML?

Ans: An anchor tag or <a> tag in HTML is used to create hyperlinks which create a path between two different HTML web pages.
		*Hyperlinks can be displayed in three ways:
		*Unvisited Link – These links are blue in color and underlined.
		*Visited Link – These links are purple in color and underlined.
		*Active Link – These links are red in color and underlined.
		
=========================================================================

Why do we use the required attribute in HTML?

Ans: The required attribute is used in HTML to make the field mandatory. It forces the user to fill that particular field to submit the form.

If the field is input then it will throw a default HTML error.

<input type="email" name = "user_email" required />

=========================================================================
How can we include Google maps on a website?

Ans: HTML Google maps allow us to display Google maps on our web page:

<!DOCTYPE html>
<html>
     <body>
            <h1>HTML Interview Questions Google Map</h1>
            <div id="map" style="width: 400px; height: 400px; background: yellow">
			</div>
			<script>
                function myMap() {
                var mapOptions = {
                           center: new google.maps.LatLng(51.5, -0.12),
                          zoom: 10
             }
                     var map = new google.maps.Map(document.getElementById("map"), mapOptions);
              }
			</script>
             <script src= "https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
	</body>
</html>

=========================================================================

Differentiate between HTML and XHTML.

Ans: Below are the differences between HTML and XHTML:
		*HTML stands for Hypertext Markup Language, whereas XHTML stands for Extensible Markup Language.
		*A static webpage is an html web page and dynamic web pages are XHTML.
		*XHTML are more stricter than HTML.
		*An XML application of HTML is defined as XHTML.
		*All modern browsers support XHTML.
		
=========================================================================

What is Web Workers?

Ans: Web Workers is a code of JavaScript which runs in the background threads without disturbing the performance of the page. It is used for computing-heavy tasks like an access database or function.

=========================================================================

What is the SVG element?

Ans: SVG is a followed XML format; it stands for Scalable Vector Graphics which is used to create vector graphics with the support for interactivity and animation.

SVG is resolution independent as it’s not losing its quality when they are resized or zoomed.

=========================================================================

 Explain about Canvas.

Ans: Canvas is a pixel-based graphics and it is one of the new features of HTML5.

It provides a space in the document where we can draw graphics by using JavaScript and it is resolution dependent, hence the quality will be affected when it’s zoomed or resized.

Example:
<!DOCTYPE html>
<html>
		<body>
				<canvas id="myCanvas" width="300" height="200" style="border:1px solid #d3d3d3; color: #c9cc18;">
				Your browser does not support the HTML5 canvas tag.</canvas>

				<script>
				var can = document.getElementById("myCanvas");
				var canvas = can.getContext("2d");
				canvas.font = "20px Hind-sanserif";
				canvas.fillText("Canvas Example",30,60);
				</script>
		</body>
</html>

=========================================================================
What is Quirks mode in HTML5?

Ans: If we do not include the <!DOCTYPE> element in our HTML page or Document, it will go to Quirks Mode. In this mode, the HTML element depends on the browser.

Hence the content will be displayed according to the browser.

=========================================================================
What is a physical tag and logical tag in HTML?
		A Physical tag has physical text which is used to tell the browser how to display the text enclosed in the physical tag.

		Example for the physical tags are: <big>, <b>, <i>

		Logical tags are used to tell the meaning of the enclosed text in it. The example of the logical tag is <Important>….</Important> tag. When we enclose text in Important tag then it tell the browser that enclosed text is more important than other text.
=========================================================================
What is a Fieldset?
	The <fieldset> is a tag in HTML that is used to group related elements in a form. It draws a box around the related elements.
=========================================================================
What is grouping in HTML?
	Grouping is used to group several HTML controls like input, textarea, selects as well as labels ( <label>) within a web form. In HTML <fieldset> element is used for Grouping.

=========================================================================
What is Cell Spacing and Cell Padding?
	Cell Spacing is referred to space/gap between the two cells of the same table.
	Cell Padding is referred to the gap/space between the content of the cell and cell wall or Cell border.
	Example:
			<table border cellspacing=3>
			<table border cellpadding=3>
			<table border cellspacing=3 cellpadding=3>

=========================================================================
What Are The Various Elements Provided By HTML5 For Media Content?
Answer.
		HTML provides the support of following elements for representing the media content.

		<audio> – It defines the sound content.
		<video> – It represents the video content that needs to be attached to a Web page.
		<source> – This tag defines the source of video and audio.
		<embed > – It provides a container for an external application.
		<track> – It defines text tracks for video and audio.
=========================================================================
What Are The New Form Elements Made Available In HTML5?
Answer.
		When we want to collect some data from the person visiting our site, we use HTML Forms. An example is, the user has to enter his name, email id when he registers for the first time.

		A form takes input from the site visitor and then posts it to a back-end application such as CGI, ASP Script or PHP script. The back-end application will then perform required processing on the passed data based on defined business logic inside the application.

		There are various form elements available in earlier version of HTML like, text fields, text area fields, drop-down menus, radio buttons, checkboxes, etc.

		HTML5 provides the support of some new Form elements that are as follows.

		<datalist> – It represents a list of pre-defined options for input controls.
		<keygen> – It defines a key-pair generator field (for forms).
		<output> – It represents the result of the calculation.

=========================================================================
What Is A Semantic Element In HTML5? Also, Explain The Difference Between Semantic And Non-Semantic Elements?
Answer.
		Semantic elements are one of the new features that are part of HTML5. They intend to help the developers in quickly creating the page structure.

		A semantic element has its meaning expressed to both the browser and the developer. Also, all the modern browsers support this feature. However, it is possible for a developer to train old browsers to handle unknown elements.

		Here is the list of some of the commonly used HTML5 Semantic Elements.
				<article>
				<figcaption>
				<figure>
				<header>
				<footer>
				<nav>
				<section>
				<article>
				<aside>
				<summary>
		
The Difference – Semantic Vs. Non-Semantic.
		Semantic – These elements clearly describe their content like <img>, <form>, <table> etc.

		Non-semantic – These elements are without any definition. They don’t describe anything about their structure such as <span> and <div>.

=========================================================================
What Are The Various Tags Provided For Better Structuring In HTML5?
Answer.
		The various tags provided for better structuring in HTML 5 are:
				<article> – This tag defines an article.
				<aside> – It defines content other than the page content.
				<bdi> – This tag isolates a part of the text for formatting in a different direction, from another text present there.
				<command> – It defines a command button to be invoked by the user.
				<details> – It outlines the additional details that a user can hide or view as per choice.
				<dialog> – It defines a dialog box.
				<figure> – This tag specifies content like illustrations, diagrams, photos, code listings, etc.
				<figcaption> – It provides a caption for a <figure> element.
				<footer> – This tag defines a footer for a document or a section.
				<header> – This tag describes a header for a document or a section.
				<hgroup> – When there are multiple levels in a heading, it groups a set of <h1> to <h6> elements.
=========================================================================
How Can We Get The Geographical Position Of A User In HTML5?
Answer.
	Yes, HTML5 can retrieve the location of a user with the use of Geolocation API. It provides getCurrentPosition() method to get the user’s current position.
=========================================================================
Describe Form Input Types In HTML5?
Answer.
		HTML5 is the new standard for HTML that provides 13 new input types for forms. Using these new input types, we can create more interactive and easy-to-use web forms. It also provides better data validation, input control, color picker controls and many others.

		The new input types for forms provided by HTML5 are as follows.
				color – It’s applicable for HTML elements that represent color.
				date – It allows the user to select a date.
				DateTime – It enables the user to select a date and time (with time zone).
				DateTime-local – It allows the user to select a date and time (without time zone).
				email – It is applicable for input fields that contain an e-mail address.
				month – It permits the user to select a month and year.
				number – It is applicable for input fields that accept a numeric value. It allows setting restriction on the data type of the number, this field takes.
				range – It is applicable for input fields that accept a value from a range of numbers. It allows setting restriction on the data type of the number, this field takes.
				search – It gets used for search fields.
				tel – It defines a field for entering a telephone number.
				time – It allows the user to select a time.
				URL – It is applicable for the input fields that contain a URL address.
				week – It allows the user to select a week and a year.

=========================================================================
What Is HTML5 Graphics?
Answer.
	In HTML5, there are two types of graphics.

	Scalable Vector Graphics (SVG).
		The HTML5 <svg> element is a container for SVG graphics. It provides several methods for drawing boxes, paths, text, circles, and graphic images.
		SVG is beneficial as nowadays, people are using high-resolution devices (iPads and Monitors), so it becomes impressive as designs, logos, and charts scale according to the requirement, maintaining the picture quality.
		SVG is XML based, which means that every element is available within the SVG DOM. It treats every shape as an object. If the user changes the attributes of any SVG object, the browser will automatically re-render the shape.
	
	Canvas.
		It is a rectangular area on the HTML page for drawing graphics on the fly, using JavaScript.
		The default size of the canvas is 300 PX × 150 PX (width × height).
		The HTML tag <canvas> is a container for the Canvas graphics. Canvas gets executed on the pixel by pixel basis.
		In Canvas, browser forgets the graphic, after drawing it. If the user tries to modify it, the entire scene needs to be redrawn, including all the objects present in the graphic.

=========================================================================
Explain The Key Differences Between SVG And Canvas?
Answer.
		Canvas is resolution dependent while SVG is not.
		Canvas does not provide any support for event handlers while SVG does provide the support for event handlers.
		Canvas is suitable for graphic-intensive games while SVG is not suitable for gaming.
		Canvas is suitable for small rendering areas while SVG is suitable for large rendering areas like Google maps.
		Canvas provides a less interactive animated user interface. Whereas, the interface provided by SVG is very highly interactive.
=========================================================================
How Can We Create A New HTML Element?
Answer.
		We can even create new elements for the document as follows.

		<script>
		document.createElement﴾"myElement"﴿
		</script>
		
		It can be used in the HTML as.

		<myElement>hello</myElement>
=========================================================================
What Is The Use Of Drag And Drop In HTML5?
Answer.
	Drag and Drop (DnD) is a powerful User Interface concept, which enables the user to copy, reorder and delete any number of items, just with the help of mouse click. To do this, the user has to click and hold the mouse button over an element, drag to the required location, and finally release the button to drop the element there.

	With HTML4, developers have to either do complex Javascript programming or use other Javascript frameworks like jQuery to achieve this functionality.

	HTML 5 introduced a Drag and Drop (DnD) API that provides the support of all the fundamental DnD operations to the browser. Thus making it easy for the developers to code it.

	Latest versions of all the main browsers, like Chrome, Firefox, and Safari, support this DnD API of HTML5.

	Drag And Drop Events.
		Many events get triggered during various stages of the drag and drop operation. 
		These events are listed below.
			dragstart – it gets triggered when the user starts dragging a draggable object.
			dragenter – it gets triggered when the user has dragged the draggable element over the target element.
			drag – it gets fired when the object is getting dragged.
			dragend – it gets fired when the user releases the mouse button after dragging an object.
			dragleave – This event gets triggered when the mouse leaves an element while a drag is occurring.
			dragover – This event gets fired when the mouse moves over an element while a drag is occurring.

=========================================================================

What Is HTML5 Web Storage?
Answer.
	HTML5 Web Storage, also known as DOM Storage is a way to preserve state on either the client or server which makes it much easier to work against the stateless nature of HTTP. It allows the web pages to store the data locally in the user’s browser.

	Following are the advantages of HTML5 Web Storage.

	It can store 5 to 10 MB data. That is far more than what cookies allow.
	HTML5 never transfers Web storage data with any HTTP request. Thus creating less overhead than cookies and in turn, increase the performance of the application.
	Apps can work both online and offline.
	This API is easy to learn and use.

=========================================================================
What Are The Different Types Of Web Storage Provided By HTML5?
Answer.
		There are two types of Web Storage.

		1. Session Storage
			As its name indicates, it stores data of current session only. The data stored in Session Storage clears on closing the browser.

			Following methods are available to access Session Storage.

			Use setItem() function to store data in Session Storage
			sessionStorage.setItem (‘key’,’value’);

			For Example.
			sessionStorage.setItem (‘username’,’Meenakshi’)
			Use getItem() function to retrieve data from Session Storage
			sessionStorage.getItem(‘key’);

			For Example.
			var username= sessionStorage.getItem(‘username’);
			We can only store String in Session Storage. To save the objects in Session, first, convert the object into JSON string and then store this string in Session Storage as in the following.
			sessionStorage.setItem (‘object’, JSON.stringify(object));

			If JSON string gets stored in Session Storage, then first convert it into an object as follows.
			var object=JSON.parse(sessionStorage.getItem(‘object’));
			Use removeItem() function to delete a particular key from Session Storage.
			sessionStorage.removeItem(‘key’);

		2. Local Storage
			Local Storage is the second type of HTML Web Storage. It stores data as KEY/VALUE pair.

			Following functions are available to access Local Storage.

			Use setItem() function to store data in Local Storage
			localStorage.setItem (‘key’,’value’);

			Use getItem() function to retrieve data from Local Storage
			localStorage.getItem(‘key’);
=========================================================================
What Is The Need Of Introducing Local Storage In HTML5?
Answer.
	Before HTML5, LocalStores was done with Cookies. They are not very good for large amounts of data, because, with every request, it passes this data to the server, making it very slow and ineffective. However, HTML5 does not pass this data on every server request. It uses the data ONLY when required. In HTML5, it is possible to store large amounts of data without affecting the website’s performance. Data for different website gets stored in separate areas. However, a particular website can only access its own data.
=========================================================================
Explain The Key Differences Between LocalStorage And SessionStorage Objects?
Answer.
		Following are the key differences between localStorage and sessionStorage objects.

			*The localStorage object stores the data without an expiry date. However, sessionStorage object stores the data for only one session.
			*In the case of a localStorage object, data will not delete when the browser window closes. However, the data gets deleted, if the browser window closes, in the case of sessionStorage objects.
			*The data in sessionStorage is accessible only in the current window of the browser. But the data in the localStorage can be shared between multiple windows of the browser.
		 

=========================================================================
What Is The Concept Of Application Cache In HTML5? What Are Its Advantages?
Answer.
	HTML5 introduced the concept of Application Cache. It means that a web application is cached, and is accessible without an internet connection.

	Following are the key advantages of Application Cache.

	Offline browsing – Users can use the application even when they are offline.
	Speed  – Cached resources load faster as compared to content that gets 
	downloaded, directly from the server.
	Reduced server load – The browser will only download updated/modified resources from
	the server.
	
=========================================================================What Is A Manifest File?
Answer.
	A Manifest file is a simple text file, that tells the browser what to cache and what not to cache.

	A Manifest file contains three Sections as

	CACHE MANIFEST – HTML5 performs the caching of files listed under this section after 
	they get downloaded for the first time.
	NETWORK – Files listed here, always need a connection to the server. The browser can never cache them.
	FALLBACK – Files listed here specify the fallback pages, if any page in it is not accessible.

=========================================================================
What Is The Difference Between HTMl5 Application Cache And Regular HTML Browser Cache?
Answer.
	Following are the key differences between the two.

	In AppCache, we can define all the assets the browser should cache in a manifest file (even the entire site). For fetching this content, it is not necessary for the user to have accessed it previously. In other words, Application Cache can prefetch pages that have not been visited at all and are thereby unavailable in the regular browser cache. However, the browser cache will only store the pages (and associated assets) the user has visited actually.
	The AppCache allows web apps (and websites) to be made available offline, that too, with the same speed benefits as the regular browser cache could provide only when the user is online.
=========================================================================
What Is A Web Worker? How Does It Work?
Answer.
		JavaScript will hang the browser if it has to handle UI events, query large amounts of API data for processing, and manipulate the DOM simultaneously.
		Web Workers handle this situation by doing all the high computation tasks without interrupting the user interface. They do this by running on separate threads. Thus we can say that.

		A web worker is a script, which runs in the background. It exists in external files.
		The user can perform actions like clicking, selecting things and so on. Meanwhile, the Web worker runs in the background.
		It is appropriate, to use Web worker for CPU intensive tasks.
		Since Web workers are in external files, they do not have access to the following JavaScript objects.

		The window object
		The document object
		The parent object
		
	How Does A Web Worker Work?
		A Web worker gets initialized with the URL of a JavaScript file that contains its code. This code sets event listeners and starts communication with the script that invoked the worker from the main page. The Syntax is as follows.

		var worker = new Worker("sample_prog.js"﴿;
		If the javascript file specified in the above code exists, the browser spawns a new worker thread.

		Once the Web worker gets spawned, it starts the communication with the parent page, using the postMessage() method. The Web worker, in turn, returns a message, that gets accessed using the onmessage() event on the main page.

		Let’s take an example, where the script spawns a Web worker to execute a loop having thousands of iterations. After that, the Web worker returns the calculated value to the HTML page.

		<script>
		var worker = new Worker('calculateLoop.js');
		worker.onmessage = function (event) {
		alert("Completed " + event.data + "iterations" );
		}; 
		</script>
		Below is the code of “calculateLoop.js” file. It makes use of postMessage() API, to pass the communication back to the HTML page.

		for (var i = 0; i <= 1000000000; i += 1){
		var j = i;
		}
		postMessage(j);
		
=========================================================================

What Are The New Attributes Provided In HTML5 For <Form>?
Answer.
	The new attributes provided in HTML5 for <form> are.

	autocomplete
		It specifies if a form or an input field should have “autocomplete” feature set as on or off.
		If autocomplete is set to on, it enables the browser to fill the values, based on the values that the user starts to enter.
		autocomplete works for input types like text, search, URL, tel, email, password, date pickers, range, and color.
	
	novalidate
		It is a boolean attribute.
		Its presence signifies that the form-data should not get validated at the time of submission.

=========================================================================
What Is Output Element In HTML5?
Answer.
	Output element gets used when you design a form, that displays the result of a computation. Along with the standard global attributes, <output> also accepts for, form, and name attributes.
	Let’s see a simple example of the <output> element that adds two numbers and displays the resulting value.

	<!DOCTYPE html>
	<html>
	<head>
	<title>HTML Output Tag</title>
	</head>
	<body>
	<form oninput="sumresult.value=parseInt(val1.value)+parseInt(val2.value)+parseInt(val3.value)">
	<input type="range" name="va1" value="10" /> +
	<input type="number" name="val2" value="20" /> +
	<input type="number" name="val3" value="40" /><br />
	The output is: <output name="sumresult"></output>
	</body>
	</html>
	
	The form attribute associates the <output> with a form. It displays the output as “70” on the web page.
=========================================================================

What Are The New Attributes Provided In HTML5 For <Input> Element?
Answer.
	Following are the new attributes provided in HTML5 for <input>.

	autofocus
		It is a Boolean attribute.
		The presence of this attribute means that an <input> element should automatically come into focus when the page gets loaded.
	
	form
		This attribute specifies about all the forms, to which a particular <input> element belongs.
	
	formaction
		This attribute defines the URL of a file, that will process the input control after the form gets submitted.
		This attribute is used along with type=”submit” and type=”image”.
		Also, it overrides the action attribute of the <form> element.
	
	formenctype
		This attribute defines, the method to encode the form data before submitting it to the server.
		It gets used with type=”submit” and type=”image”.
		Also, it overrides the enctype attribute of the <form> element.
	
	formmethod
		It defines the HTTP method used for sending form related data to the action URL.
		It gets used with type=”submit” and type=”image”.
		It overrides the method attribute of the <form> element.
	
	formnovalidate
		It is a boolean attribute.
		It gets used with type= “submit”.
		It indicates that the validation of the <input> element, should not be done at the time of submission.
		It overrides the novalidate attribute of the <form> element.
	
	formtarget
		It specifies a name or a keyword of the area where response received after submitting the form will be displayed.
		It gets used with type=”submit” and type=”image”.
	
	height and width
		It specifies the height and width of an <input> element.
		It gets used only with <input type=”image”>.
	
	list
		It refers to a <datalist> element, which contains a list of pre-defined options for an <input> element.
	
	min and max
		It specifies the minimum and maximum value for an <input> element.
		It works with the following input types, number, range, date, datetime, datetime-local, month, time, and week.
	
	multiple
		It is a boolean attribute.
		It specifies that the user is allowed to enter more than one value in the <input> element.
		It works with the following input types: email and file.
	
	pattern
		It specifies a regular expression with which the value of the <input> element gets compared.
		It works with the following input types: text, search, URL, tel, email, and password.
	
	placeholder
		It displays a short hint that indicates the expected value of an input field.
		It works with the following input types: text, search, URL, tel, email, and password.
	
	required
		It is a boolean attribute.
		It indicates that it is mandatory to fill the particular field, before submitting the form.
	
	step
		It specifies the legal number intervals for an <input> element.
		It works with the following input types: number, range, date, datetime, datetime-local, month, time, and week.
=========================================================================

What Is The Major Difference Between Transitional And Strict Doctype?
Answer.
	Strict – This DTD contains all HTML components and properties. However, it does NOT INCLUDE presentational or expostulated components (like text style). It does not permit the use of Framesets.
	
	Transitional – This DTD contains all HTML components and properties, INCLUDING presentational and belittled components (like textual style). It does not allow the use of Framesets.
=========================================================================

What Is Audio Tag In HTML 5? What Are Its Attributes>
Answer.
	This new element allows you to embed audio files in an HTML or XHTML document, without the need for any plug-ins. The Audio tag is a new tag introduced in HTML5. You can use it to play audio sound like .mp3, wav, and .ogg. 
	Using the <source> tag, we can specify media along with media type and many other attributes. An audio element allows multiple source elements and browser will use the first recognized format.

			<!DOCTYPE HTML>
			<html>
			<body>

			<audio controls="controls" >
			<source src="URL1" type="audio/mp3" />
			<source src="URL2" type="audio/wma" />
			<source src="URL3" type="audio/x-wav" />
			Your browser does not support the audio element.
			</audio>

			</body>
			</html>
	The HTML5 audio tag supports following attributes to direct the look and feel and various functionalities of the control.

	autoplay
		It is a boolean attribute. If, the value is set the audio track starts playing automatically. The System will not wait for data loading to complete.
	
	autobuffer
		It is a boolean attribute. If set, the audio will automatically begin buffering, even if the automatic play is not enabled.
	
	controls
		If this attribute is present, it will allow the user to control audio playback, including volume, seeking, and pause/resume playback.
	
	loop
		Setting this boolean attribute would automatically restart the audio from the beginning, once it reaches to the end.
	
	preload
		This attribute specifies that the audio will be loaded at page load, and will be ready to run. If autoplay is present, this attribute will not work.
		
	src
		It represents the URL of the audio to embed. Its presence is optional.

=========================================================================

What Is The Use Of <Fieldset> Tag In HTML5?
Answer.
		The <fieldset> tag groups related form elements. It is like a box. In other words, it draws a box around related elements.

		It must start with a <legend>tag because the <legend> tag defines the title of the fieldset.

		Following is the Syntax of the <fieldset> tag in HTML5.

		<fieldset>Controls</fieldset>
		All the popularly known browsers provide the support for the <fieldset> tag.

		HTML5 supports following attributes with the fieldset tag.

		disabled
			Its value is disabled. It specifies, whether the fieldset will be displayed or not.
		
		name
			Its value is in the form of text. It defines the name of the fieldset.
		
		form
			Its value is the name of the form. It specifies the form related to the fieldset.
		
		Let’s see an example, where we create a fieldset in a form. Here we use the <legend> tag to define the heading for the fieldset.

				<html> 
				<body> 
				<form> 
				<fieldset> 
				<legend>Personal Information</legend> 
				First Name: <input type="text" /> 
				<br/><br/> Last Name: <input type="text" /> 
				<br/><br/> person_Address: <input type="text" /> 
				<br/><br/> person_Qualification: <input type="text" /> 
				</fieldset> 
				</form> 
				</body> 
				</html>
=========================================================================

What Are The HTML Tags Which Get Deprecated In HTML5?
Answer.
	Following are the tags that are deprecated in HTML5.
		<basefont>
		<big>
		<center>
		<font>
		<s>
		<strike>
		<tt>
		<u>
		<frame>
		<frameset>
		<noframe>
		<acronym>
		<applet>
		<isindex>
		<dir>
		
	Some attributes from HTML4 are no longer allowed in HTML5 since their functionality is better handled by CSS. Below are some of the known attributes that got removed and the corresponding impacted element.
			Attribute Removed Element
			rev, charset a, link
			longdesc, name img
			version html
			abbr th
			scope td
			align all block level elements
			background body
			hspace, vspace img
			bgcolor table, tr, td, th
			border, cell padding, cell spacing table
			height, width td, th
			valign table

=========================================================================

What Is A Meter Tag? What Is The Difference Between Progress Tag And A Meter Tag?
Answer.
		The <meter> tag defines a scalar measurement within a known range or a fractional value. We can also call it a gauge.
		Some of the items that can be represented using <meter> tag are Disk usage, the relevance of a query result, and so on.

		Note: The <meter> tag should not be used to indicate progress (as in a progress bar). For progress bars, use the <progress> tag.

		Following example demonstrates the use of the <meter> tag.

		<li><meter min="0" max="100" value="25">25%</meter></li>
		
		The <meter> tag provides the support of the following attributes.

		min
			It is a number. It specifies the minimum value of the range.
			
		max
			It is a number. It specifies the maximum value of the range.
		
		low
			It is a number. It defines a range that represents <low> value.
		
		high
			It is a number. It defines a range that represents “high” value.
		
		value
			It is a number. It is a mandatory element. It defines the current value of the gauge.
		
		optimum
			It is a mandatory element with a numeric value. It specifies the optimum, or the best value, for the element. If this value is higher than the “high” value, this indicates that the higher the value, the better it is. If it’s lesser than the <low> mark, it means that the lower values are better. If it is, in between, then it indicates that neither high nor low values are good.
		
		form
			It specifies one or more forms that define the <meter> element. It has value form_id.


=========================================================================

Explain the layout of HTML?
	HTML layout specifies a way in which the web page is arranged.
	Every website has a specific layout to display content in a specific manner.

Following are different HTML5 elements which are used to define the different parts of a webpage.
		<header>: It is used to define a header for a document or a section.
		<nav>: It is used to define a container for navigation links
		<section>: It is used to define a section in a document
		<article>: It is used to define an independent, self-contained article
		<aside>: It is used to define content aside from the content (like a sidebar)
		<footer>: It is used to define a footer for a document or a section
=========================================================================
What are empty elements?
	HTML elements with no content are called empty elements. For example: <br>, <hr> etc.
=========================================================================
What is the use of a span tag? Give one example.
	The span tag is used for following things:	
		For adding color on text
		For adding background on text
		Highlight any color text
		
		Example:

		<p>  
		<span style="color:#ffffff;">  
		In this page we use span.  
		</span>  
		</p>

=========================================================================
What are the entities in HTML?
	The HTML character entities are used as a replacement for reserved characters in HTML. You can also replace characters that are not present on your keyboard by entities. These characters are replaced because some characters are reserved in HTML.


=========================================================================
Why is a URL encoded in HTML?
	An URL is encoded to convert non-ASCII characters into a format that can be used over the Internet because a URL is sent over the Internet by using the ASCII character-set only. If a URL contains characters outside the ASCII set, the URL has to be converted. The non-ASCII characters are replaced with a "%" followed by hexadecimal digits.

=========================================================================
https://www.techbeamers.com/latest-html-interview-questions/

https://career.guru99.com/top-50-html-interview-questions/

https://www.softwaretestinghelp.com/html-interview-questions/
