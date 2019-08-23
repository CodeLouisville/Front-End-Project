# Code Louisville Front-End Web Development

## Week 3: ###

### 1. Add The following code to the HTML document. ###

```html

<!-- Section: Downloads -->

<section class="downloads">

  <div class="container">

    <header>

      <h2>Learn how to build websites, mobile apps and more</h2>

      <p>One of the best ways to start coding is by building websites. Whether you want to tweak your business’s site, hone your web development skills, or learn to collaborate with developers, we’ll help you get there.</p>

    </header>

  </div>

</section>

```

And this css to the stylesheet:

```CSS

.header-content {
	margin: 4em auto;
	max-width: 74ch;
}


/* Download Section */

.downloads {
	background: #e8e8e8;
	color: #171717;
	padding: 3em;
}

.downloads h2 {
	text-align: center;
}

.badges {
	margin-top: 3em;
	padding: 0;
	text-align: center;
}

```


**Things to mention during this time:**

  * Talk about hierarchy with H1, H2, etc..
  * Font basics, readability and accessibility
  * Reusable/Modular CSS - BEM, OOCSS, SMACSS, Dry, Subclasses



### 2. Add the Open Sans font code snippet to index.html above the existing stylesheet. Also update the font stack in the stylesheet. ###

```HTML

<!-- Link to External Google font -->
<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i,800,800i&display=swap" rel="stylesheet">

```

```CSS

body {
  font-family: 'Open Sans', sans-serif;
}

```

**Things to mention during this time:**

  * Font Stack
  * Various options for hosting webfonts (local, external, services like Adobe, Google, Font-Squirrel).



### 3. Add code snippets for Features section.  ###

```HTML

<!-- Section: Features -->

<section class="features">

  <div class="container">

    <header class="header-content">

      <h3>It’s time to start investing in yourself</h3>

      <p>Learning to code has never been so much fun before! We have made the learning experience fun and interactive. You will enjoy it like a game while learning and upgrading your skills.</p>

    </header>

    <div class="features-group">

        - Items go here -

    </div>

  </div>

</section>

```

```CSS

/* Features Section */

.features {
	background: #FFFFFF;
	color: #171717;
	padding: 3em;
}

.features h3 {
	text-align: center;
	margin-bottom: 2rem;
}

.features-group {
	margin-bottom: 3em;
}

```


### 3. Add the 3 *features-item* divs, content and CSS.  ###


```HTML

<div class="features-item">

  <div class="features-item-img">

    <img src="img/feature-learn-photo.png" alt="Person working on laptop" />

  </div>

  <div class="features-item-txt">

    <h4>Learn by Doing</h4>

    <p>From building websites to analyzing data, the choice is yours. Not sure where to start? We’ll point you in the right direction.</p>

  </div>

</div>

```

```HTML

<div class="features-item">

  <div class="features-item-img">

    <img src="img/feature-practice-photo.png" alt="Photo of computer screens with code" />

  </div>

  <div class="features-item-txt">

    <h4>Put your learning into practice</h4>

    <p>No matter your experience level, you’ll be writing real, working code in minutes.</p>

  </div>

</div>

```

```HTML

<div class="features-item">

  <div class="features-item-img">

    <img src="img/feature-dreamjob-photo.png" alt="Photo of people working" />

  </div>

  <div class="features-item-txt">

    <h4>Land your dream job</h4>

    <p>Coding skills have never been more in-demand. Learn everything you need to take your career to the next level.</p>

  </div>

</div>

```

```CSS

.features-item {
	display: flex;
	flex-wrap: wrap;
	flex-direction: column;
	margin-bottom: 2em;
}

.features-item-txt,
.features-item-img {
	align-self: center;
}

.features-item-txt {
	padding: 0;
	text-align: left;
	flex: 1;
}

```



  **Things to mention during this time:**

    * Flexbox
    * Psuedo elements, nth-child



## Student Challenge ##

### 1. Go to Google Fonts http://google.com/fonts and switch out the font family.  ###

### 2. Review the mockup. Look at the different ways **features-group** is laid out depending on the viewport(screen) size. Add styles to the the stylesheet to replicate the layouts from the mockup. Do it without changing the HTML *(HINT: :nth-child)*. Use the existing media queries in the stylesheet. ###

### 3. Review the mockup. Add the app store badges. Images are included in the *img* folder.  ###


----




## Student Challenge - Answers ##

### 1:  ###

```HTML

<!-- Link to External Google font -->
<link href="https://fonts.googleapis.com/css?family=Ubuntu:300,300i,400,400i,500,500i,700,700i&display=swap" rel="stylesheet">

```

```CSS

body {
  font-family: 'Ubuntu', sans-serif;
}

```

### 2: Features Group Items ###

Tablet Media Query:

```CSS

.features-item {
  flex-direction: row;
}

.features-item-txt,
.features-item-img {
  align-self: center;
  flex: 1;
}

.features-item-txt {
  padding-left: 2em;
}

```

Desktop Media Query:

```CSS

.features-item {
  flex-direction: row;
}

.features-item:nth-of-type(odd) {
  flex-direction: row-reverse;
}

.features-item-txt,
.features-item-img {
  align-self: center;
}

.features-item-txt {
  padding: 0 2em;
  flex: 1;
}

```
