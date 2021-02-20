# Intro
    - Front End is what people see (User Interface)
      - HTML, CSS, JavaScript
      - Bootstrap.
    - Back End is what happens in the background to make everything work. (Functionality)
      - .NET, Ruby, Python, PHP, Java, NodeJS, SQL

# Bootstrap
    - Bootstrap is a bunch of code written to be reusable so that you can drop it into your website and make designing much easier. 
    - Bootstrap was developed by Twitter, to get more consistency across websites they design. 
      - Free & Open-Source now. You can see all the source code on GitHub.
-  https://github.com/twbs/bootstrap

## What does Bootstrap allow you to do?
	  - More & more people are moving away from desktops into mobile platform usage.
	  - So a lot of websites need to be responsive to the viewport. Adaptable layout.
	    - It should have a different layout for ipad, desktop, phone.
	  - Pre-Styled Elements.
	    - Like a CSS Button Generator can easily be done with BootStrap.

### EXAMPLE: Blue Button Generator HTML & CSS
	HTML: 
	<body>
	<a href="#" class="myButton">blue</a>
	</body>

	CSS: 
	.myButton {
		box-shadow:inset 0px 1px 0px 0px #97c4fe;
		background:linear-gradient(to bottom, #3d94f6 5%, #1e62d0 100%);
		background-color:#3d94f6;
		border-radius:6px;
		border:1px solid #337fed;
		display:inline-block;
		cursor:pointer;
		color:#ffffff;
		font-family:Arial;
		font-size:15px;
		font-weight:bold;
		padding:6px 24px;
		text-decoration:none;
		text-shadow:0px 1px 0px #1570cd;
	}
	.myButton:hover {
		background:linear-gradient(to bottom, #1e62d0 5%, #3d94f6 100%);
		background-color:#1e62d0;
	}
	.myButton:active {
		position:relative;
		top:1px;
	}


### EXAMPLE: Blue Button Generator BootStrap 4
	<body>
	    <button class="btn btn-primary">Hello Word</button>
	</body>

## How Does BootStrap Work?
- Inside the BootStrap Source files, bootstrap-5.0.0-beta2\dist\css\bootstrap.css
- When you open the bootstrap.css file, you will see A LOT of predefined styles for the HTML elements. 
- There is also a lot of classes that are already styled. 
- TAG SELECTORS & CLASS SELECTORS are already styled. 

## How to add Bootstrap to our websites?
### Method 1:
Copy and past this into header section of HTML code. 

	This is how to add Bootstrap to our website by linking it in header.
	ADD: link rel="stylesheet"...The browser will download the boostrap files if the user doesn't have it cached already.
	Bootstrap used CDN: Content Delivery Network; It will access the files quickly by reaching shortest route.
	    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">


### Method 2:
If creating website completely from scratch you can add Starter template.

	<!doctype html>
	<html lang="en">
	  <head>
	    <!-- Required meta tags -->
	    <meta charset="utf-8">
	    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	    <!-- Bootstrap CSS -->
	    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">

	    <title>Hello, world!</title>
	  </head>
	  <body>
	    <h1>Hello, world!</h1>

	    <!-- Optional JavaScript; choose one of the two! -->

	    <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
	    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
	    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-Piv4xVNRyMGpqkS2by6br4gNJ7DXjqk09RmUpJ8jgGtD7zP9yug3goQfGII0yAns" crossorigin="anonymous"></script>

	    <!-- Option 2: Separate Popper and Bootstrap JS -->
	    <!--
	    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
	    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
	    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js" integrity="sha384-+YQ4JLhjyBLPDQt//I+STsc9iw4uQqACwlvpslubQzn4u2UU2UFM80nGisd026JF" crossorigin="anonymous"></script>
	    -->
	  </body>
	</html>
