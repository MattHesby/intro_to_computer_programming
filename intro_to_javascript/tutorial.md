## Introduction to JavaScript
Let's see how we can use the JavaScript programming language to do a very simple task: get a website to alert our name, and also to print our name.

#### Making Your HTML File
Make a file called `hello_javascript.html`.

This file is going to combine your knowledge of HTML as well as JavaScript.

Put the following into your file:

```html
<!DOCTYPE HTML>
<html>
	<head>
	</head>
	<body>
	</body>
</html>
```

This is the empty skeleton of an .html file. Try opening it up in your favorite web browser.

You should see an blank website.

Let's break down what each of the parts of the above HTML file do:

```html
<!DOCTYPE HTML>
```
This species to your browser that the file is an HTML file.

```html
<html>
	<head>
	</head>
	<body>
	</body>
</html>
```
This contains the actual content of the website. All HTML files have a header with content enlosed by the <head> </head> tags. 

HTML files also have a body, which is contained inside the <body> </body> tags.

#### Adding User Input
Add the following two lines of code between the <body> </body> tags:

``` html
		<h1 id="name-header">Hello </h1>
		<input type="text" id="name-box">
```

Try opening your web browser. You should see a website with with the text `Hello` and an input box.

#### Adding Buttons
Now add the following two lines of code in the <body> </body> section, below the two lines you just added.

```html
<button>Press to alert</button>
<button>Press to put name</button>
```

Refresh your page, and now you see two buttons on the website! However, pressing the buttons currently doesn't do anything.

Now **here** is where JavaScript comes in.

Before you go onto the next section, make sure that your HTML file looks like the following:

```html
<!DOCTYPE html>
<html>
	<head>
	</head>
	<body>
		<h1 id="name-header"> </h1>
		<input type="text" id="name-box">
		<button>Press to alert</button>
		<button>Press to put name</button>
	</body>
</html>
```

### Adding JavaScript
#### Adding the <script> Tag
We want our first button to pop an alert on our screen that says "Hello".

In the <head> </head> section, add the following:

```html
<script>
</script>
```

This is called the <script> tag. Between the opening <script> and the closing </script> tag you can put JavaScript! Let's get ready to rock-n-roll with some actual JavaScript now.

#### Writing Our First JavaScript Function
Inside of the <script> </script> tags, we're going to write a function. Put the following function inside the tags:

```javascript
<script>
			function say_hello() {
				alert("Hello there!");
			};
</script>
```

```html
<script>
			function say_hello() {
				alert("Hello there!");
			};
</script>
```
