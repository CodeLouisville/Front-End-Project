# Code Louisville Front-End Web Development

## Week 2: ###

### 1. Present wireframes and mockup of site. ###

**Things to mention during this time:**

  * Brief overview of the Wireframe and Mockup processes
  * Mention Wireframe and Mockup tools (Adobe XD, Sketch, Balsamic, Invision, Adobe Photoshop, etc..)

### 2. Download zip file, and distribute to class (https://github.com/CodeLouisville/Front-End-Project/archive/Week-2.zip). Make sure students have setup a Code Louisville project folder and extract the files to a new folder. ### 

**Things to mention during this time:**

  * Keep files organized, make sure folders are created for images, css, and javascript.
  * File/folder hierarchy.
  * Relative and Absolute file paths.
  * Filename conventions: lowercase, CamelCase,  

### 3. Open **index.html** in code editor. Give overview of the different parts of the html page. ### 

**Things to mention during this time:**

  * Doctype, html, head tags and their purpose.
  * Page title, viewport meta, other meta tags.
  * Body, header, main, aside, footer tags.

### 4. Add CSS file link to page. ### 

  ```html
<link rel="stylesheet" href="css/style.css" />
  ```

  **Things to mention during this time:**

  * Re-iterate relative/absolute file paths.
  * External, Internal (head), Inline stylesheets.

### 5. Open **css/style.css** in code editor. ### 

  **Things to mention during this time:**

  * Normalize and Resets (similarities and differences).
  * Basic text properties and values.

###  6. Replace the existing < header > code with the following into **index.html**. Class names have been provided to help.


```html
<header class="nav-header" role="banner"> <!-- Header Begin -->

  <div class="container row">

  <div class="nav-logo column">

    <a href="/" title="Go to home page">
      <img src="img/codelou-app-logo.png" alt="CodeLou.App logo" role="img" />
    </a>

  </div>

  <nav role="navigation" class="column">

    <ul id="menu">

      <li><a href="#">About Us</a></li>
      <li><a href="#">Download</a></li>
      <li><a href="#">Features</a></li>
      <li><a href="#">Contact Us</a></li>

    </ul>

  </nav>

  </div>

</header> <!-- Header End -->
  ```

### 7. Copy and Paste the following code into **index.html** between < main > and </ main >. ### 

  ```html

    <!-- Section: Hero -->

    <section class="hero">

      <div class="container row">

        <div class="hero-copy column">

          <h1>It’s time to start investing in yourself</h1>

          <p class="hero-txt">CodeLou.app is a simple, fast and interactive app, to learn any programming language. Our learning platform is available in Android, iOS and web with over 6 Million+ downloads worldwide.</p>

          <a href="#" class="btn">Learn More</a>

        </div>

        <div class="hero-img column">

          <img src="img/app-mockup.png" alt="Image of application on phone" />

        </div>

      </div>

    </section>

  ```

### 8. Add these utility classes to the external stylesheet. ### 

   ```css
   /* Utility classes */

   .container {
   	width: 100%;
   	max-width: 1000px;
   	margin: 0 auto;
   }

   .row {

   }

   .column {

   }

   img {
   	max-width: 100%;
   	height: auto;
   }
   ```


### 9. Add these classes for the **Hero** section to the external stylesheet. ### 

  ```css

  /* Hero Section */

  .hero {
  	background-color: #AE1347;
  	color: #FFFFFF;
  	padding: 2em;
  }

  .hero-img img {
  	max-width: 300px;
  	margin: 0 auto;
  }

  ```

## Student Challenge ##

### 1. Using the given classes (.row, .column) create a 2 column layout with Flex-box. ### 

### 2. Create a .btn class with :hover state using the following parameters: ### 

  * Background Color: #32A952.
  * Border: 1 pixel, solid outline, and colored #2FA74D.
  * Uppercase text and bold.
  * Border radius of 12 pixels.
  * Hover state color of #288641.

### 3. Add background image to hero section using the supplied image in the **img** folder with the filename *hero-background.jpg*. The background image should not repeat and be centered. Update the background color to #171717. ### 




----




## Student Challenge - Answers ##

### 1: 2 Column layout with Flexbox ### 


  ```css

  .row {
  	display: flex;
  	flex-direction: row;
  	flex-wrap: wrap;
  	width: 100%;
  }

  .column {
  	display: flex;
  	flex-direction: column;
  	flex-basis: 100%;
  	flex: 1;
  }

  ```

### 2. Button ### 

```css

.btn {
  background-color: #32A952;
	-moz-border-radius: 12px;
	-webkit-border-radius: 12px;
	border-radius: 12px;
	border: 1px solid #2FA74D;
	cursor: pointer;
	color: #FFFFFF;
	font-family: sans-serif;
	font-size: 1.25em;
	font-weight: bold;
	padding: 0.5em 1em;
	text-decoration: none;
	text-transform: uppercase;
	width: 100%;
	max-width: 300px;
	text-align: center;
	display: block;
}

.btn:hover {
	background-color: #288641;
}

```

### 3. Hero background ### 

```css

.hero {
	background-color: #171717;
	background: url('../img/hero-background.jpg');
	background-repeat: no-repeat;
	background-position: center;
	background-size: cover;
	color: #FFFFFF;
	padding: 4em 2em;
}

```
