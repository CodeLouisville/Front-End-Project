# Code Louisville Front-End Web Development

Wireframe/Mockup Link: https://xd.adobe.com/view/f899dba9-9609-4127-459d-deecf932ccca-8ea8/

Working Site: https://codelouisville.github.io/Front-End-Project/

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


### 3. BONUS: Built-in HTML5 Form Validation Styling ###


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

### 4. Add the following snippet for the footer. ###


```HTML

<footer> <!-- Footer Begin -->

  <div class="container ftr-grid">

      <div class="ftr-container">

      <h4>Contact Us</h4>

      <address>
      1234 Main St.<br />
      Louisville, KY 40213<br />
      E: info@codelouisville.org<br />
      P: 502-555-5555
      </address>

      </div>

      <div class="ftr-container">

      <h4>Sitemap</h4>

        <ul class="sitemap-links" role="navigation">

          <li><a href="#">About Us</a></li>
          <li><a href="#">Download</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="#">Contact Us</a></li>

        </ul>

      </div>

      <div class="ftr-container">

      <h4>Follow Us</h4>

        <ul class="social-links">

          <li><a href="#"><img src="img/ico-linkedin.png" alt="Social icon to linkedin.com" role="img" /></a></li>
          <li><a href="#"><img src="img/ico-instagram.png" alt="Social icon to instagram.com" role="img" /></a></li>
          <li><a href="#"><img src="img/ico-twitter.png" alt="Social icon to twitter.com" role="img" /></a></li>
          <li><a href="#"><img src="img/ico-facebook.png" alt="Social icon to facebook.com" role="img" /></a></li>
          <li><a href="#"><img src="img/ico-youtube.png" alt="Social icon to youtube.com" role="img" /></a></li>

        </ul>

      </div>

</div>

<div class="copyright">

  <div class="container row">

    <span>&copy; Copyright 2019 Code Louisville</span>

    <span><a href="#">Privacy Policy</a> | <a href="#">Terms of Use</a></span>

  </div>

</div>

</footer> <!-- Footer End -->

```


## Student Challenge ##

### 1. Review the mockup and finish building the footer *(HINT: Use CSS Grid)*. ###

### 2. Make the main navigation menu in the header responsive. ###

### 3. Accessibility check: make sure your site is accessible. ###


----
