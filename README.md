# HTML Cheat Sheet :nerd_face:
Listed below are some of the most used HTML tags, their syntax and some examples.

## A very basic HTML Structure :atom:
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

## Headings :atom:
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

## Paragraph :atom:
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

## Bold text :atom:
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

## Emphasize text :atom:
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

## Links :atom:
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

##  Opening links on a new tab :atom:
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

## Lists (Unordered list) :atom:
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

## Lists (Ordered list) :atom:
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

## Table :atom:
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


## Tags :white_check_mark:
| 	Tag 	    | 	Syntax                      | Description 	                                                     |
| 	:---:       |     :---:                     |	:---:                                                            |
| DOCTYPE  	    | `<!DOCTYPE>`                  | Defines the document type                                          |
| Html          | `<html></html>`               | The container for all other HTML elements                          |
| Head          | `<head></head>`               | Document info                                                      |
| Body          | `<body></body>`     		    | Where the magic happens                                            |
| Title         | `<title></title>`    		    | Gives your document a title                                        |
| Comments      | `<!--Something in here-->`    | Won't be parsed by the browser                                     |
| Headings      | `<h1></h1>...<h6></h6>`       | HTML Headings                                                      |
| Paragraph     | `<p></p>`                     | Defines a paragraph                                                |
| Strong        | `<strong></strong>`           | It bolds the text                                                  |
| Emphasize     | `<em></em>`                   | Emphasizes the text                                                |
| Links         | `<a href=""></a>`             | It creates a relationship between a document and an external source|
| Unordered list| `<ul></ul>`                   |Defines an unordered list 										     |
| Ordered list  | `<ol></ol>`                   |Defines an ordered list 										     |
| Table         | `<table></table>`             |Defines a table 										             |
| thead         | `<thead></thead>`             |Table heading										                 |
| tbody         | `<tbody></tbody>`             |The body content in a table 										 |
| tr            | `<tr></tr>`                   |Table row 										                     |
| th            | `<th></th>`                   |Header cell in a table 										     |
| td            | `<td></td>`                   |Table data 										     |









