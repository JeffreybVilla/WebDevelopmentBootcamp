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

EXAMPLE: Blue Button Generator HTML & CSS
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


EXAMPLE: Blue Button Generator BootStrap 4
<body>
    <button class="btn btn-primary">Hello Word</button>
</body>
