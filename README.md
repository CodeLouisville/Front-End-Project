# Code Louisville Front-End Web Development

## Week 4: ###

### 1. Add the code snippets below to build out the Call to Action section. ###

```html

<!-- Section: Call to Action -->

<section class="call-to-action">

  <div class="container">

    <header class="header-content">

      <h3>Wanna start coding?</h3>

      <p>Learn the technical skills you need for the job you want. As leaders in online education and learning to code, we’ve taught hundreds in the Louisville community.</p>

    </header>



  </div>

</section>

```

```CSS

/* CTA Section */

.call-to-action {
	background: #e8e8e8;
	color: #171717;
	padding: 3em;
}

.call-to-action h3 {
	text-align: center;
	margin-bottom: 2rem;
}

```

### 2. Add the form snippet below the </ header >. Copy the CSS to the stylesheet. ###


```HTML

<form action="#" class="cta-form">

  <label for="email">Email: (required)
  <input type="email" name="email" id="email" placeholder="joe@example.com" required />
  </label>

  <input id="terms" type="checkbox" name="terms" value="terms" required /> <label for="terms"> I have read the Privacy Policy and agree to the Terms of Service.</label>

  <input type="submit" name="submit" value="Subscribe" class="btn btn-center" />

</form>

```

```CSS

.cta-form {
	padding-bottom: 1.25444em;
	text-align: left;
	max-width: 600px;
	margin: 0 auto;
}

.cta-form label {
	font-size: 0.8em;
	font-weight: normal;
}

.cta-form input[type=email] {
	font-size: 1.25em;
	width: 100%;
	margin: 0 0 2em;
	min-width: 200px;
	border: 1px solid #333333;
	border-radius: 6px;
	transition: border-color .5s ease-out;
	padding: 1em;
}


.cta-form input[type=checkbox] {
	margin: 0 0 2em;
	border: 1px solid #333333;
	border-radius: 6px;
	transition: border-color .5s ease-out;
}

.cta-form input[type=checkbox]:focus {
	outline: 3px solid #5cbf2a;
	border-color: transparent;
}


```

**Things to mention during this time:**

  * Forms, Form styling, labels
  * CSS transitions, animations
  * Accessibility, tab order, screen readers


### 3. BONUS. Built-in HTML5 Form Validation Styling ###


```CSS

.cta-form input[type=email]:optional {
	border-color: #999999;
}

.cta-form input[type=email]:required {
	border-color: #333333;
}

.cta-form input[type=email]:invalid {
	border-color: #E72465;
	color: #E72465;
}

.cta-form input[type=email]:focus {
	outline: 3px solid #5cbf2a;
	border-color: transparent;
}

.cta-form input[type=email]:valid {
	border-color: #5cbf2a;
	color: #5cbf2a;
}

```

## Student Challenge ##

### 1. X. ###

### 2. X. ###

### 3. X. ###


----




## Student Challenge - Answers ##

### 1:  ###







