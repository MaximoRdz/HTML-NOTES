# HTML-CSS-NOTES
## Basic Structure
```html
<!DOCTYPE html>
<html>
	<!--This html contains all the content of the document-->
	<head>
		<!--Metadata information that will not be rendered, check also open graph-->
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width">
		<title>Title that will appear when browsing this page</title>
		<meta name="description" content="Page content description 
		displayed together with the title when browsed">
	</head>
	<body>
		<!--Contains everything that WILL BE RENDERED-->
	</body>
</html>
<!--This is a comment-->
```
## Tags 
Used to create HTML elements
1. Headers 
	All the way up from "h1" to "h6"
	```html
	<h1>This is the title 1</h1>
	```
1. Paragraph 
	```html
	<p>This is a paragraph</p>
	```
1. Lists
	1. Ordered List
		```html
		<ol>
			<li>List Element</li>
		</ol>
		```
	1. Unordered List
		```html
		<ul>
			<li>List Element</li>
		</ul>
		```
1. Nested Elements
	Defined inside other HTML elements.
	```html
	<p>This is a paragraph with a <strong>nested element</strong>.</p>
	```
## Embed Elements
They are embed in the text, it is not necessary to close the label.
1. Images
	```html
	<img 
		width=200
		height=200
		title="Related info to the image"
		alt="Alternative in case the image is not displayed properly" 
		src="./images/profile.png"
	>
	```
1. Inputs
	```html
	<input type="{button, checkbox, color, email, date, ...}">
	```
## Attributes
They provide additional information to HTML elements, they can be **global** (`id`, `class`, …) or **specific** to that element (`src` is specific to images).
## Semantic HTML
+ `Header`: 
+ `Footer`:  
+ `Section`: Independent parts of the content
+ `Article`: Element with self contained information such that it could be extracted and move anywhere and it would keep its meaning.
+ `Aside`: Supplementary information somewhat related to the main content
+ `Main`: Principal content of the page that makes it unique 
+ `Small`: Secondary explanation or clarification. 
## Loading lazy
Load images only when required by the user. Optimizing the page resources. 
```html
<img loading="lazy" src="...">
```
## Iframes
They allow us to embed another webpage into ours.
## Adding Styles
```html
<!DOCTYPE html>
<html>
	<!--This html contains all the content of the document-->
	<head>
		<!--Metadata information that will not be rendered, check also open graph-->
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width">
		<title>Title that will appear when browsing this page</title>
		<meta name="description" content="Page content description 
		displayed together with the title when browsed">
		
		
		<style>
			<!--
		<style/>
	</head>
	<body>
		<!--Contains everything that WILL BE RENDERED-->
	</body>
</html>
<!--This is a comment-->
```
## References
1. [MDN Web Docs (mozilla.org)](https://developer.mozilla.org/en-US/)
1. [CSS Documentation](https://lenguajecss.com/)
1. [Learn CSS](https://web.dev/learn/css?hl=es)