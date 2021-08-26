<!-- we are going to create a landing page using html css-->
<!-- this tutorial is entirely for beginners -->

<!-- colors -  -->

--lightgray:#f8f9fa 
--white : #fff


<!-- font family -->
 <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&display=swap" rel="stylesheet">


font-family: 'Lato', sans-serif;

<!-- i am using following vscode plugins -->

<!-- text-editor used is VS Code -->
<!-- plugins are emmet, prettier code formatter and live server to create own server -->
<!-- go to plugins folder and download -->
<!-- we will learn few basics about html and  css first -->

<!-- tags are most important part of html lets learn few -->

<!-- heading tags -->
<!-- heading tags are h1,h2,h3,h4,h5,h6  lets see -->

<!-- this is how inline css is written -->
<h1 style="text-align: center">Hello World</h1>
<!--largest font size-->
<h2 class="heading-3">hello world</h2>
<!--large font size-->
<h3>hello world</h3>
<!--medium font size-->
<h4>hello world</h4>
<!--small font size-->
<h5>hello world</h5>
<!--small font size-->
<h6>hellow world</h6>
<!--smallest font size-->

<!-- heading tags are used for declaring headings in different sections of html page -->

<!-- paragraph tag -->

<!-- paragraph tag is used to insert text content its widely used in html page -->

<!-- image tag -->

<img src="./images/terminal.svg" alt="" />
<!-- imagge tag is used to insert images in webpage -->

<!-- anchor tag -->

<a href="https://startbootstrap.com/previews/landing-page" target="_blank"
	>Landing page</a
>
<!-- target_blank opens web page in new window -->
<!-- anchor tag is used to create hyper links within the page or outside the website -->
<!-- href is attribute that takes url to point to -->

<!-- div and section tag -->
<!-- bot tags create block of elements -->
<!-- section tag is collection of element within perticular section where as div tag has no real meaning. its just used to define block of code -->
<!-- header tag is used for header purpose -->
<!-- nav tag is used to create navigation -->
<!-- footer tag for footer purpose -->

<!-- we are going to see all these while designing -->

<!-- css basics -->
<!-- css needs class or id attribute to target styles to perticular element -->

<!-- lets apply some basic css -->
<!-- css can be written inline, on same page or in external page -->
<!-- on page css is written inside style tag -->
<style>
	/* text-align:center is basic style to center the text  */
	/* we can also use text-align:left, text-align:right to position element */
	/* to specify size we use font-size property */
	/* font size can be used in pixels,rem or em  1rem = 16px 1em = 16px, it is good practice to use rem or em */
	/* color property gives color to element */

	/* it is always good practice to use classnames in order to target them in css */
	/* classneames are selected using . in css */
	/* another property is font-weight */
	/* there are 3 attributes to font weight bol,bolder,normal but heading ususally are in bold */
	/* 		text-transform: capitalize; capitalize the element */
	.heading-3 {
		text-align: center;
		font-size: 30px;
		color: red;
		font-weight: normal;
		text-transform: uppercase;
	}

	/* these are few styles we will learn more while developing */
</style>
