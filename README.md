# :arrow_right: HTML Cheat Sheet :arrow_left:
Listed below are some of the most used HTML tags, their syntax and some examples.

---

## Table of contents
1. [Basic HTML Structure](#a-very-basic-html-structure)
2. [Headings](#headings) 
3. [Paragraph](#paragraph) 
4. [Rendering text in bold](#rendering-text-in-bold) 
5. [Rendering text in italic](#rendering-text-in-italic) 
6. [Links](#links) 
7. [Opening links in a new tab](#opening-links-in-a-new-tab) 
8. [Unordered list](#unordered-list) 
9. [Ordered-list](#ordered-list) 
10. [Table](#table) 
11. [Form](#form) 
12. [Defining sections in a form](#defining-sections-in-a-form) 
13. [Text area in a form](#text-area-in-a-form) 
14. [Drop-down list](#drop-down-list) 
15. [Inserting a button](#inserting-a-button) 
16. [Inserting an image](#inserting-animage) 
17. [Wrapping an image with a link tag](#wrapping-an-image-with-a-link-tag) 
18. [Quoting](#quoting) 
19. [Abbreviation](#abbreviation) 
20. [Cite](#cite) 
21. [Tags](#tags) 

---

### A very basic HTML Structure
```html
<!DOCTYPE html>
<html>
 	<head>
		<title>Page Title</title>
   	</head>
   	<body
   	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Headings
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Headings-->
		<h1>Heading one</h1>
		<h2>Heading two</h2>
		<h3>Heading three</h3>
		<h4>Heading four</h4>
		<h5>Heading five</h5>
		<h6>Heading six</h6>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Paragraph
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Paragraph-->
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Rendering text in bold 
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Bold text-->
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation <strong>ullamco laboris nisi ut aliquip</strong> ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p> 
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Rendering text in italic 
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Emphasize text-->
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation <em>ullamco laboris nisi ut aliquip</em> ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p> 
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Links
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Links-->
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation <a href="">ullamco laboris nisi ut aliquip</a> ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p> 
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

###  Opening links in a new tab
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Links on new tab-->
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation <a href="https://www.google.com/" target="_blank">ullamco laboris nisi ut aliquip</a> ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p> 
	</body>
</html>
```
:warning: Be sure to use target attribute `target="_blank"`

###### [Back to ](#table-of-contents) :top:
---

### Unordered list
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!-- Unordered Lists-->
		<ul>
			<li>Item 1</li>
			<li>Item 2</li>
			<li>Item 3</li>
			<li>Item 4</li>
			<li>Item 5</li>
			<li>Item 6</li>
		</ul>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Ordered list
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!-- Ordered Lists-->
		<ol>
			<li>Item 1</li>
			<li>Item 2</li>
			<li>Item 3</li>
			<li>Item 4</li>
			<li>Item 5</li>
			<li>Item 6</li>
		</ol>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Table
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Table-->
		<table>
			<thead>
				<tr>
					<th>First Name</th>
					<th>Last Name</th>
					<th>Email</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Henrique</td>
					<td>Prata</td>
					<td>henrique@email.com</td>
				</tr>
				<tr>
					<td>Flora</td>
					<td>Morgan</td>
					<td>flora@email.com</td>
				</tr>
				<tr>
					<td>Star</td>
					<td>Wars</td>
					<td>star@email.com</td>
				</tr>
			</tbody>
		</table>	
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Form
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!-- Form-->
		<form>
			<label for="fname">First name:</label><br>
  			<input type="text" id="fname" name="fname"><br>
  			
  			<label for="lname">Last name:</label><br>
  			<input type="text" id="lname" name="lname"><br>
  			
  			<label for="email">Email:</label><br>
  			<input type="text" id="email" name="email">
		</form>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Defining sections in a form
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!-- Form with div -->
		<form>
			<div>
				<label for="fname">First name:</label><br>
  				<input type="text" id="fname" name="fname">
  			</div>
  			
  			<div>
  				<label for="lname">Last name:</label><br>
  				<input type="text" id="lname" name="lname">
  			</div>
  			
  			<div>
  				<label for="email">Email:</label><br>
  				<input type="text" id="email" name="email">
  			</div>
		</form>
	</body>
</html>
```
:warning: The _for_ attribute of the `<label>` tag should be equal to the _id_ attribute of the `<input>` tag <br>
:warning: To define a sections use the `<div>` tags

###### [Back to ](#table-of-contents) :top:
---

### Text area in a form
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Form with <textarea> -->
		<form>
			<div>
				<label>Please leave us a message:</label><br>
  				<textarea name="message"></textarea>
  			</div>
  		</form>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Drop-down list
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<!--Drop-down list-->
  		<div>
  			<label for="colors">Choose a color:</label>

			<select name="colors" id="colors">
  				<option value="blue">Blue</option>
  				<option value="green">Green</option>
  				<option value="red">Red</option>
  				<option value="purple">Purple</option>
			</select>
		</div>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Inserting a button
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
  		<!--Button-->
		<button>Click Me</button>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Inserting an image
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
  		<!--Image-->
		<button>Click Me</button>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Wrapping an image with a link tag
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
  		<!-- Wrapping an image with a link tag-->
			<a href="img/ghost.svg" target="_blank">
				<img src="img/ghost.svg" alt="Just a ghost image">
	   		</a>
	 </body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Quoting
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
	<!--Quotations-->
	 <blockquote cite="https://www.google.co.uk/">
		Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
	    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
	    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
	    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
	    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
	    proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	    </blockquote>
	 </body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Abbreviation
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<p>The <abbr title="National Aeronautics and Space Administration">NASA</abbr>is the agency in charge of the civilian space program</p>

	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Cite
```html
<!DOCTYPE html>
<html>
	<head>
		<title>HTML Cheat Sheet</title>
	</head>
	<body>
		<p> <cite>On Writing</cite> by Stephen King</p>
	</body>
</html>
```
###### [Back to ](#table-of-contents) :top:
---

### Tags 
| 	Tag 	     | 	Syntax                      | Description 	                                                     |
| 	:---:        |     :---:                    |	:---:                                                            |
| DOCTYPE  	     | `<!DOCTYPE>`                 | Defines the document type                                          |
| Html           | `<html></html>`              | The container for all other HTML elements                          |
| Head           | `<head></head>`              | Document info                                                      |
| Body           | `<body></body>`     		    | Where the magic happens                                            |
| Title          | `<title></title>`    		| Gives your document a title                                        |
| Comments       | `<!--Something in here-->`   | Won't be parsed by the browser                                     |
| Headings       | `<h1></h1>...<h6></h6>`      | HTML Headings                                                      |
| Paragraph      | `<p></p>`                    | Defines a paragraph                                                |
| Strong         | `<strong></strong>`          | It bolds the text                                                  |
| Emphasize      | `<em></em>`                  | Displays text in italic                                            |
| Links          | `<a href=""></a>`            | It creates a relationship between a document and an external source|
| Unordered list | `<ul></ul>`                  |Defines an unordered list 										     |
| Ordered list   | `<ol></ol>`                  |Defines an ordered list 										     |
| Table          | `<table></table>`            |Defines a table 										             |
| thead          | `<thead></thead>`            |Table heading										                 |
| tbody          | `<tbody></tbody>`            |The body content in a table 										 |
| tr             | `<tr></tr>`                  |Table row 										                     |
| th             | `<th></th>`                  |Header cell in a table 										     |
| td             | `<td></td>`                  |Table data 										                 |
| Form           | `<form></form>`              |Defines a form for user input										 |
| Label          | `<label></label>`            |Label for an input element 										 |
| Input          | `<input></input>`            |Input control 										     			 |
| Line break     | `<br>`                       |Single line break 										     		 |
| Horizontal rule| `<hr>`                       |Displays a horizontal line 										 |
| Div            | `<div></div>`                |It defines a section in the document 							     |
| Text are       | `<textarea></textarea>`      |Defines a box for multiline input							         |
| Select list    | `<select></select>`          |Drop-down list							                             |
| Option         | `<option></option>`          |Defines possible options in a drop-down list	                     |
| Button         | `<button></button>`          |A clickable button	                                                 |
| Image          | `<img>`          			|Used to insert images                                               |
| Quotations     | `<blockquote></blockquote>`  |A section quoting an external source                                |
| Abbreviation   | `<abbr></abbr>`              |An abbreviation or an acronym                                       |
| Cite           | `<cite></cite>`              |The title of a work in italic                                       |




















