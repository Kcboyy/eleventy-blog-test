---
layout: layouts/base.njk
eleventyNavigation:
  key: Contact
  order: 3
---
# Contact Me

Please fill in the form below and we will get back to you shortly.

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label><b>First Name:</b><br><input type="text" name="name" placeholder="Enter first name" /></label>
  </p>
  <p>
    <label><b>Surname:</b><br><input type="text" name="name" placeholder="Enter surname"/></label>
  </p>
  <p>
    <label><b>Your Email:</b><br><input type="email" name="email" placeholder="Enter email"/></label>
    <br><small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </p>
    
  <p>
    <label><b>Message:</b><br><textarea name="message" placeholder="Your message"></textarea></label>
  </p>
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">I have read and agreed to the <span style="color:blue;font-weight:bold">Terms & Conditions</span></label>
  </div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
<br>

<i><b>Thanks for visiting!